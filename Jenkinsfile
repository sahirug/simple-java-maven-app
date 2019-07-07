node {
    stage('Building') {
        docker.image('maven:3-alpine').inside {
	        sh 'ls -la'
            sh 'mvn clean install -U'
        }
    }
    stage('Testing') {
        sh 'ls -la'
    }
}