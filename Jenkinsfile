pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ezemirallas/jenkinstest.git'
            }
        }
    }
}
