pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh 'git --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		sh 'java -version'
            }
        }
    }
}
