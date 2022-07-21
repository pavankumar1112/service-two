pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'clean package', quietPeriod: 600, wait: true)
      }
    }

  }
}