pipeline {
    agent any
    stages {
        stage('Shell1') {
            steps {
                sh 'docker build -t eisgraus/apache:v1 .'
                sh 'docker run -d -p 8446:80 apache:v1'
            }
        }
    }
}
