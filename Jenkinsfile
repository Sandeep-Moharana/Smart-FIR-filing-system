pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
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
