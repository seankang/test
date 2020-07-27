pipeline {
  agent {
    dockerfile {
      filename 'test'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'echo "test"'
      }
    }
  }
  environment {
    param1 = '1'
    param2 = '2'
  }
}