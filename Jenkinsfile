pipeline {
    agent any

    stages {
        stage('paso1') {
            steps {
				sh "mvn verify -Pperformance"
            }
        }
    }
}