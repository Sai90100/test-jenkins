pipeline {
    agent any

    stages {
        stage('Print Greeting') {
            steps {
                echo 'Hello Jenkins'
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed'
        }
    }
}