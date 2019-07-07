node {
    stage('Building') {
        docker.image('maven:3-alpine').inside {
            sh 'mvn clean install -U'
        }
    }
    stage('Testing') {
        sh 'ls -la'
    }
}