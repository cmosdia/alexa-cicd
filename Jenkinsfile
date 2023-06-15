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
        bat 'mvn -Dmaven.test.failure.ignore=true install'
      }
    }
    stage('Test') {
      steps {
       
      }
    }
    stage('Deploy') {
      steps {
        archiveArtifacts 'target/*.war'
       
      }
    }
  }
}
