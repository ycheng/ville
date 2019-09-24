
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pwd'
                sh 'env'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
