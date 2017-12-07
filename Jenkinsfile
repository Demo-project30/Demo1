pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'echo " This is Build Stage"'
            }
        }
        stage('Test'){
            steps {
               sh 'echo "This is a Test Stage"' 
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo "This is a Deploy Stage"'
            }
        }
    }
}
