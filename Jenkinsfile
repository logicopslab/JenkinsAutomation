pipeline {
  agent { label 'node-1' }
  stages {
    stage('CheckOut') {
      steps {
        git "https://github.com/logicopslab/JenkinsAutomation.git"
      }
    }
    stage('Operation File #1') {
      steps {
         bat "First.bat"
      }
    stage('Operation File #2') {
      steps {
         bat "Second.bat"
      }
    }
  }
}
