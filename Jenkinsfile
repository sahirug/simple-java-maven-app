pipeline {
	agent {
		docker {
			image 'maven:3-alpine'
			args '-v /root/.m2:/root/.m2'
		}
	}
	stages {
		stage ('Greeting') {
			steps {
				sh 'echo "Hello world"'
			}
		}
	}
}
