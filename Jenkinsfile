pipeline {
    agent any

    stages {
        stage('Print Greeting') {
            steps {
                echo 'Hello Jenkins'
                error'dont say
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed'
            echo 'I will always say Hello again!'
            deleteDir()
        }

        failure {
            echo 'I will run when pipeline is failed'
        }

        success {
            echo 'I will run when pipeline is success'
        }
    }
}