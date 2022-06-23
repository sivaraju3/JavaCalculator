pipeline {
    agent any

    stages {
        stage('validate') {
            steps {
                echo 'validating..'
                sh 'validate'
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
