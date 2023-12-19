pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout from Github. Testing webhook, verify'
            }
        }
        stage('build') {
            steps {
                echo 'Build project'
            }
        }
        stage('test'){
            steps{
                echo 'testing the code'
            }
        }
        stage('infra creation'){
            steps{
                echo 'provisioning infrastructure'
            }
        }
        stage('deployment'){
            steps{
                echo 'Deplying the code'
            }
        }
    }
}
