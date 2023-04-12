pipeline {
  agent any
  trigger {
    cron('H/15 * * * *')
  }
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the tigger'
      }
    }

  }
}
