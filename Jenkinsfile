pipeline {
  agent any
  stages {
    stage('git checkout') {
      steps {
        git(branch: 'master', credentialsId: 'chaitanya2020j', url: 'https://github.com/chaitanya2020j/game-of-life')
      }
    }
    stage('read POM') {
    stage('build') {
      steps {
        build 'pom.xml'
      }
    }
   }
  }
}
