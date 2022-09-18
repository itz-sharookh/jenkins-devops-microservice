
// Declarative Pipeline

pipeline{
	agent any
	stages{
		stage('Build'){
			steps {
					echo "Build"
			}
		}

		stage('Test'){
			steps {
					echo "Test"
			}
		}

		stage('Integration Test'){
			steps {
					echo "Integration Test"			
			}
		}

	} 
	post{
		always {
			echo "I am Awesome. I run always"
		}

		success {
			echo "I run when the build is successful"
		}

		failure {
			echo "I run when the build is failed."
		}

	}
}


// Scripted Pipeline

// node{
// 	echo "Build"
// 	echo "Test"
// 	echo "Integration Test"
// }


// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Integration Test"
// 	}
// }
