pipeline {
    agent {label "project_slaveA"}
    stages {
        stage('Build') {
            steps {
                echo 'Building the Project...'
                // commands to build the project
            }
        }
        stage('Test') {
            steps {
                echo 'Running Tests..'
                // commands to run test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to Production...'
                // commands to deploy to production
            }
        }
        stage('Monior') {
            steps {
                echo 'Monitoring the production environment'
                //commands to monitor the production environment
            }
        }
    }
}
