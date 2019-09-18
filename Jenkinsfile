pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        sh 'docker build -t simple-flask-app:latest .'
        sh 'docker run -d -p 5000:5000 simple-flask-app'
      }
    }
    stage('Deploy') {
      steps { 
        sh 'ls'
      }
    }
  }
}