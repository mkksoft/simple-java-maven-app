pipeline {
    agent any
    tools {
        maven 'maven3'  // This must match the name you gave
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
