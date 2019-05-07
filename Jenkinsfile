pipeline {
  agent any
  stages {
    stage('Test Stage') {
      steps {
        echo 'Hello World'
        mail(subject: 'Jenkins Test', body: 'Hello', to: 's.cooney@colart.com')
      }
    }
  }
}