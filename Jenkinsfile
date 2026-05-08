pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build the code using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run tests using JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scan vulnerabilities using Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run staging tests using Postman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to AWS EC2 production server'
            }
        }
    }
}
