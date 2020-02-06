pipeline {
  agent {
    dockerfile {
      filename 'syka'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}