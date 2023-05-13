pipeline {
	agent any
	stages {
		stage('Build') {
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
	} post {
		always {
			echo "This always runs!"
		}
		success {
			echo "Ran successfully"
		}
		failure {
			echo "ERROR: Failed run"
		}
	}
}
