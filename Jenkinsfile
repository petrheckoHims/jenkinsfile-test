pipeline {
  agent any
  stages {
    stage('Echoing') {
      steps {
        sh """
          echo 'job name: ${env.JOB_NAME}'
          echo 'job URL: ${env.BUILD_URL}'
        """
        }
      }
  }
}
