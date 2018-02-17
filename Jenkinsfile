pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }
<<<<<<< HEAD
    environment {
        CI = true
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
=======
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
>>>>>>> 65142e0a5b5cb755ea12040804e5168df3fe2c43
    }
  }
}