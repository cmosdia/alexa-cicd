pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Starting the pipeline'
       
      }
    }
    stage('Build') {
      steps {
         echo 'build'
      }
    }
    stage('Test') {
      steps {
        echo 'test'
      }
    }
    stage('Deploy') {
      steps {
        archiveArtifacts 'target/*.war'
       
      }
    }
  }
}
