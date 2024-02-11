//library identifier: 'jenkins-shared-library-directory@main'

pipeline {
    agent {
        docker {
            image 'nginx'
        }
    }
    stages {
        stage('Test') {
            steps {
                script {
                    hello_world()
                }
            }
        }
    }
}
