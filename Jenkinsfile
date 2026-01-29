
pipeline {
    agent any
    stages {
        stage('Install') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }
        stage('Run App') {
            steps {
                sh 'python3 app.py &'
            }
        }
    }
}
