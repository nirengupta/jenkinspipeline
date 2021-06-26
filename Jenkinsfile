pipeline {
  agent any
  stages {
    stage('codecollection') {
      steps {
        git(url: 'https://github.com/nirengupta/jenkinspipeline.git', branch: 'main', poll: true, changelog: true)
      }
    }

    stage('Code building') {
      steps {
        git(credentialsId: 'Peoplechoise@1', url: 'nirengupta/jenkinspipeline', branch: 'main', poll: true)
      }
    }

  }
}