pipeline {
    agent any

    stages {
        stage('1') {
            steps {
                echo 'Hello World'
            }
        }
        stage('2') {
            steps {
                echo 'Hello World'
            }
        }
        stage('3') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always {
            emailext body: 'LOL', subject: 'LOL', to: 'sachin1@gmail.com'
        }
    }
}
