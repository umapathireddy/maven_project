pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/umapathireddy/maven_project.git', changelog: true, poll: true)
      }
    }
  }
}