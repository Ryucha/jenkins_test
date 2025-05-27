pipeline {
    agent any


    triggers {
        githubPush()  // GitHub 푸시 시 항상 빌드
    }

    
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
            }
        }
    }
}