pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'github-token', url: 'https://github.com/Sandeep-Moharana/Smart-FIR-filing-system.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build your project here (e.g., npm install, mvn package)"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Run tests here (e.g., npm test, mvn test)"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploy logic here (e.g., docker run, scp to server)"'
            }
        }
    }
}
