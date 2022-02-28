pipeline {
  agent any
  stages {
    stage("Build") {
      steps {
        sh 'pwd'
        sh 'echo "Hello Jenkins!"'
        sh '''
          echo "Let\'s connect with Github."
          seq 1 10
        '''
      }
    }
  }
}
