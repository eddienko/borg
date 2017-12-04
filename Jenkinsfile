pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'python -c "import sys; print(sys.path)"'
      }
    }
  }
}