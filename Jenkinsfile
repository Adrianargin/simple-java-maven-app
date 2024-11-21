pipeline {
    agent any
    tools {
        maven 'apache-maven-3.9.9'  // Esto asegura que se use la versión correcta
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}