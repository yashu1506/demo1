pipeline {
  agent any
  stages{
    stage('test') {
      steps{
        echo "this is test"
      }
    }
    stage('clone') {
      steps{
        git branch: 'yashvi', url: 'https://github.com/yashu1506/demo1.git'
    }
  }
}
