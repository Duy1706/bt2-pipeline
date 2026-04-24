pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building.. Tu dong chay bang Webhook!"
                sh 'echo "doing build stuff.."'
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh 'echo "doing test stuff.."'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh 'echo "doing delivery stuff.."'
            }
        }
    }
}
