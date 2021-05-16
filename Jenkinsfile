pipeline {
    agent any
    stages {
        stage('build') {
            steps {
				echo "Build"
            }
        }
		stage('Test') {
            steps {
				echo "Test"
            }
        }
		stage('Integration Test') {
            steps {
				echo "Integration Test"
            }
        }
    } 
	post {
		always{
			echo "I am awesome. SuI always run"
		}
		success {
			echo "I am awesome. Success"
		}
		failure {
			echo "I am awesome. Failure"
		}
	}
}

