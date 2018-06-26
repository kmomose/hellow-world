pipeline {
  agent any
  stages {
    stage('in') {
      steps {
        git 'https://github.com/kmomose/hellow-world.git'
      }
    }
    stage('build') {
      steps {
        sh 'echo "build stage"'
      }
    }
    stage('test') {
      steps {
        sh 'echo "JUNIT test"'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "deploy application"'
      }
    }
  }
}