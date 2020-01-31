pipeline {
  agent any
  stages {
    stage('Request To Clone Rebates Production Environment') {
      steps {
        build 'MANUAL_ACTIVITY'
      }
    }

    stage('Create Sandbox Environment with Production Copy') {
      steps {
        build 'MANUAL_ACTIVITY'
      }
    }

  }
}