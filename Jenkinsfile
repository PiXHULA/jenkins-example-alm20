pipeline {
    agent any
    stages {
        stage ('Fetch code') {
            steps {
                sh 'ls'
            }
        }
        stage ('build') {
            steps {
                sh 'mvn --version'
            }
        }
        
        stage ('Run tests') {
            steps {
                sh 'ls'
            }
        }
        
        stage ('Publish test results') {
            steps {
                sh 'java --version'
            }
        }
    }
}
