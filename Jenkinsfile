pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo hello'
        echo 'Pulling...' + env.BRANCH_NAME
        echo 'id = ' + env.CHANGE_ID
      }
    }
  }
}
