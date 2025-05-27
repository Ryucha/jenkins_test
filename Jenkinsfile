pipeline {
    agent any
    
    stages {
        stage("Clone") {
            steps {
                git url: 'https://github.com/Ryucha/jenkins_test.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building..."'
            }
        }
    }
}