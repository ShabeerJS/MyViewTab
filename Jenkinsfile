pipeline {
    agent any

 

    stages {
        stage('Compile') {
            steps {
                echo 'Hello World'
                bat  'atlas-compile'
            }
        }
       stage('Package') {
            steps {
                echo 'Hello World'
                bat  'atlas-package'
            }
        }
       stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
}