pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'dotnet build' // For Windows
            }
        }

        stage('Run the tests') {
            steps {
                bat 'dotnet test --no-build --verbosity normal' // For Windows
            }
        }
    }
}
