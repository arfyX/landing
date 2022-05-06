pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                yarn i
		yarn build
		echo 'Build'
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
