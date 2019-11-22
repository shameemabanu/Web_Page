pipeline {
    agent any
    tools { 
        maven 'maven' 
        jdk 'jdk8' 
    }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
