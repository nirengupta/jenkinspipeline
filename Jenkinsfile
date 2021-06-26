pipeline {
  agent any
  stages {
    stage('codecollection') {
      steps {
        git(url: 'https://github.com/nirengupta/jenkinspipeline.git', branch: 'master', poll: true, changelog: true, credentialsId: 'Peoplechoise@1')
      }
    }

  }
}