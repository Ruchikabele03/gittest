pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo "Building.."
                sh 'ls -l'
            }
        }
        stage("Test") {
            steps {
                echo "Testing.."
                sh 'date'
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploying...."
                sh 'time'
            }
        }
    }
}