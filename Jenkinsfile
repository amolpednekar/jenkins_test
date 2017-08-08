pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
				javac Test.javac
				java Test
            }
        }
    }
}