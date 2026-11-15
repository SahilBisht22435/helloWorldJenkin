pipeline {
    agent any

    stages {
        stage('Check Python') {
            steps {
                bat '"C:\\Users\\Dell\\AppData\\Local\\Programs\\Python\\Python315\\python.exe" --version'
            }
        }

        stage('Run Hello World') {
            steps {
                bat '"C:\\Users\\Dell\\AppData\\Local\\Programs\\Python\\Python315\\python.exe" helloWorldSahil.py'
            }
        }
    }
}