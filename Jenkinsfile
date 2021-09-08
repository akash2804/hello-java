pipeline {

    agent {
        docker {
            image 'nginx'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'docker -version'
            }
        }
        
    }
}
