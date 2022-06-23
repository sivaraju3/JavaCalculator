pipeline {
    agent any

    stages {
        stage('validate') {
            steps {
                echo 'validating..'
                sh 'mvn validate'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'mvn test'
            }
        }
        stage('build') {
            steps {
                echo 'bulding....'
                sh 'mvn package'
            }
        }
    }
}
