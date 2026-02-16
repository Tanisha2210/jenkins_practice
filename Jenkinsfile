pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout stage'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
post {
    success {
        echo 'Build Successful!'
    }
    failure {
        echo 'Build Failed!'
    }
}
