pipeline {
    agent any

    stages {
        stage("Check Webhook") {
            steps {
                sh "echo webhook-delivery-successful"
            }
        }
        stage("Test") {
            steps {
                sh "echo test-successful"
            }
        }
    }
}
