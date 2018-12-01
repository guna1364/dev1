pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building new project'
        sh 'echo " using new blue ocean pipe"'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }
  }
  environment {
    devops = 'DVOPS'
  }
}