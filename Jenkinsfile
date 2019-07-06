pipeline {
	agent {
		docker {
			image 'maven:3-alpine'
			args '-v /root/.m2:/root/.m2'
		}
	}
	stages {
		stage ('Building-JAR') {
			steps {
				sh 'mvn clean install -U'
			}
		}
		stage ('Building-Docker-Image') {
			steps {
				sh 'ls -la'
			}
		}
	}
}
