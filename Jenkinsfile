
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Le workspace est pret'
            }
        }

        stage('Build') {
            steps {
                echo 'Build en cours'
                sh 'echo Build OK'
            }
        }

        stage('Test') {
            steps {
                echo 'Execution des tests'
                sh 'echo Tests OK'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Simulation du deploiement'
                sh 'echo Deploiement OK'
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
