pipeline {
    agent any

    stages {
        stage('code validation') {
            steps {
                echo 'validating..'
                sh 'mvn validate'
            }
        }

    stages {
        stage('unit test') {
            steps {
                echo 'testing..'
                sh 'mnv test'
            }
        }
    }
}
