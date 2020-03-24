pipeline {
  agent any
  stages {
    stage("Build"){
      steps {
        sh "build install"
      }
    }
    stage("Tests"){
      steps {
        sh "echo 'simulando um teste automatizado'"
      }
    }
  }
}