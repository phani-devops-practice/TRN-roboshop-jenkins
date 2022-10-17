pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage('Create Job') {
      steps {
        sh 'ansible-playbook create-job.yml'
      }
    }
  }
}

