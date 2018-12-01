pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building new project'
            sh 'echo " using new blue ocean pipe"'
          }
        }
        stage('') {
          steps {
            sh '/bin/sh /d/jenkins_installed/sample.sh'
          }
        }
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