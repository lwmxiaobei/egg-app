pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                
	            sh 'npm i'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}
