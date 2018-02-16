pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Hello I\'m herere'
          }
        }
        stage('MavenTest') {
          steps {
            bat 'C:/apache-maven-3.5.2/bin/mvn test'
          }
        }
      }
    }
  }
}