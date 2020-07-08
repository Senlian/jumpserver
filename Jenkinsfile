pipeline {
  agent {
    docker {
      image 'nginx'
    }

  }
  stages {
    stage('t1') {
      steps {
        git(url: 'https://github.com/Senlian/jumpserver', branch: 'master')
      }
    }

  }
}