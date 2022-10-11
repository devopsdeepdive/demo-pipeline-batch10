pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/demo-pipeline-batch10.git', branch: 'master', credentialsId: 'github-user')
      }
    }

  }
}