pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Le code est disponible dans le workspace'
            }
        }

        stage('Build') {
            steps {
                echo 'Build en cours'
                bat 'echo Build OK'
            }
        }

        stage('Test') {
            steps {
                echo 'Execution des tests'
                bat 'echo Tests OK'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Simulation du deploiement'
            }
        }
    }

    post {
        success {
            echo 'Pipeline termine avec succes'
        }
        failure {
            echo 'Le pipeline a echoue'
        }
    }
}
