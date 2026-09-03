pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests using JUnit and Selenium.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Performing security scan using OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to a staging AWS EC2 server.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on the staging environment using Selenium.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to the production AWS EC2 server.'
            }
        }
    }
}
