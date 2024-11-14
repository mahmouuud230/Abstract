pipeline {
    agent any
    stages {
        stage('Checkout repo') {
            steps {
                git 'https://github.com/mahmouuud230/Abstract.git'
            }
        }

        stage('Print the file content') {
            steps {
                sh 'cat text'
           
            }
        }

        stage('Cleaning Jenkins Workspace') {
            steps {
                deleteDir()
           
            }
        }
    

    }
}
