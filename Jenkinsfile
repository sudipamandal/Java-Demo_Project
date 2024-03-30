pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/sudipamandal/Java-Demo_Project.git'
            }
        }
        
        stage('Build') {
            steps {
                // Invoke Maven and build the project
                sh 'mvn clean install'
            }
        }
    }
}
