pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Build stage
                    sh './gradlew assemble'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Test stage
                    sh './gradlew test'
                }
            }
        }

        // You can add more stages as needed
    }
}
