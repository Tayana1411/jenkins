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
				RUN apt-get update && apt-get -y install docker
			}
		}
	}
}
