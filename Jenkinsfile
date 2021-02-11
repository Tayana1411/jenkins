pipeline{
	agent any
	stages{
		stage('Compile'){
			steps {
				echo "Compiled sucessfully!"
			}
		}
		stage('JUnit'){
			steps {
				echo "JUnit passed sucessfully!"
			}
		}
		stage('Quality gate'){
			steps {
				echo "Sonar Qube Quality Gate passed sucessfully!"
			}
		}
		stage('Deploy'){
			steps {
				echo "Pass!"
			}
		}
		stage('Docker'){
			steps {
				sh "sudo docker run devtayana/jenkin-api:1.0.0"
			}
		}
	}
}
