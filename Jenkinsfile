pipeline{
  agent any
  stages{
    stage('make directory'){
      steps{
        sh "mkdir ~/jenkins-tutorial-test"
        }
    }
    stage('make files'){
      steps{
        sh "touchd ~/jenkins-tutorial-test/file1 ~/jenkins-tutorial-test/file2"
        }
    }
  }
}
