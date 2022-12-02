pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stages {
       stage('Build Artifact') {
       sh 'mvn clean package'
} 
    }
}