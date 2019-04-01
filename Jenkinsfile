pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/umapathireddy/maven_project.git', branch: 'master', poll: true)
      }
    }
    stage('compile') {
      steps {
        sh 'mvn package'
      }
    }
  }
}