pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
                ls
                '''


            }
        }
        stage('Test') {
            steps {
                sh '''
                ls
                '''


            }
        }
    }

    post {
        always {
            echo 'This will always run after the stages complete.'
        }
        success {
            echo 'This will run only if all stages succeed.'
        }
        failure {
            echo 'This will run only if any stage fails.'
        }
    }
}
