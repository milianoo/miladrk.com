pipeline {
  agent any
  stages {
    stage('clone files') {
      steps {
        sh 'echo \'build is working\''
      }
    }
    stage('send email') {
      steps {
        mail(subject: 'Deployed', body: 'Deployed', from: 'milad@devnest.io', to: 'milad.rk@live.com')
      }
    }
  }
}