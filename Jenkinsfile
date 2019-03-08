pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Demo', propagate: true)
      }
    }
  }
}