pipeline {
  agent none
  stages {
    stage('say hello') {
      agent { label 'nodejs-app' }
      steps {
        container('nodejs') {
          echo 'Hello World!'   
          sh 'java -version'
        }
      }
    }
  }
}
