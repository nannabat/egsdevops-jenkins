pipeline {
    agent any
    triggers {
        cron('0 0 * * *')
    }
    options {
        timeout(time: 10, unit: 'MINUTES')
        buildDiscarder(logRotator(numToKeepStr: '5', daysToKeepStr: '10'))
    }
    stages {
        stage('Build') {
            steps {
                echo 'Starting build...'
               
               
               
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server...'
               
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server...'
               
            }
        }
    }
}

