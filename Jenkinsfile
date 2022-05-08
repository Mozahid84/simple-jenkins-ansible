pipeline {
  agent any
  stages {
    stage ('Anisble Run Playbook') {
      steps {
        ansiblePlaybook (
        simple.yml
        )
      }  
    }
  }
}
