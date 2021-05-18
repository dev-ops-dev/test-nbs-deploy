pipeline {
  agent {
    node {
      label '4CE9371LQD'
    }

  }
  stages {
    stage('Init') {
      steps {
        echo 'Start init'
      }
    }

    stage('Get files from TFS') {
      steps {
        echo 'Get files from TFS'
      }
    }

    stage('Get files from Shared drive') {
      steps {
        echo 'Get files from share drive'
      }
    }

    stage('Update Web.config') {
      steps {
        echo 'Backup original file'
        echo 'Update web.config'
      }
    }

    stage('NBS API Deployment') {
      steps {
        echo 'Copy files to target nodes'
        echo 'Run scripts'
      }
    }

    stage('NBS POI deployment') {
      steps {
        echo 'NBS POI deployment'
      }
    }

    stage('DMTM API Deployment') {
      steps {
        echo '4.	DMTM API Deployment'
      }
    }

  }
  environment {
    DEV = 'DEV'
  }
}