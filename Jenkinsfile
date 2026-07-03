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
post { 
            always { 
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
}