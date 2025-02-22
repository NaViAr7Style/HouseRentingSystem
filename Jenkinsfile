pipeline {
    agent any

    stages {
        stage('Build the project') {
            steps {
                bat 'dotnet build'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'dotnet test'
            }
        }
    }
}
