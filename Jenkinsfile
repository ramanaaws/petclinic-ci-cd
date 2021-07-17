pipeline {
  agent any
  stages {
    stage('main') {
      steps {
        build(job: 'tomcat', quietPeriod: 1, wait: true)
      }
    }

  }
}