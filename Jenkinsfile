pipeline {
  agent any

  stages {
    stage('Create Job') {
      steps {
        sh 'ansible-playbook create-job.yml'
      }
    }
  }
}

