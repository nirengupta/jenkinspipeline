pipeline {
  agent any
  stages {
    stage('codecollection') {
      steps {
        git(url: 'https://github.com/nirengupta/jenkinspipeline.git', branch: 'main', poll: true)
      }
    }

  }
}