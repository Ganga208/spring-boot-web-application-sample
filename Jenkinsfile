@Library("my-shared-libraries") _
pipeline {
    agent {label 'jdk-21'}
    stages {
        stage('Checkout') {
            steps {
                helloWorld()
            }
        }
        stage('Build using Maven') {
            steps {
                mavenBuild()
            }
        }
    }
}