pipeline {
agent any

  stages {
    stage('compile and package code') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}