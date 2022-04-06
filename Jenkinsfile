  pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo "this is testing is done"
      }
    }
    stage('git clone') {
      steps {
        git branch: 'yashvi', url: 'https://github.com/yashu1506/demo1.git'
      }
    }
  }
}
