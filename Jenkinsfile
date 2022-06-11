pipeline {
      agent {
		kubernetes {
          inheritFrom 'ubuntu'
		}

    stages {
        stage('Hello') {
            steps {
                sh '''
                df -h
                '''
            }
        }
    }
}