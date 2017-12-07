pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'echo "I am your 1st Child"'
            }
        }
        stage('Test'){
            steps {
               sh 'echo "you are my master"' 
            }
        }
        stage('Deploy') {
            steps {
               sh 'echo "assign me tasks"'
            }
        }
    }
}
