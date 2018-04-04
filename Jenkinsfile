pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'make' 
            }
        }
        stage('Test'){
            steps {
                echo'reports/**/*.xml' 
            }
        }
        stage('Deploy') {
            steps {
                echoc 'make publish'
            }
        }
    }
}
