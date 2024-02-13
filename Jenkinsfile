@Library('mrt3-jenkins-library@master') _

pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        mrtBuildForJar()
      }
    }
  }


  environment {
    SUB_MODULE_NAME = ''
    APPLICATION_NAME = 'CICD_test'
    SPRING_PROFILES_ACTIVE = ""
  }
}
