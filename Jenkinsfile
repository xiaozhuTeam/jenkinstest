pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
            		echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                sh 'make'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}