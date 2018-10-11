pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'hello world'
          }
        }
        stage('') {
          steps {
            emailext(subject: 'hello', body: 'world', to: 'berkut2012@hotmail.com')
          }
        }
      }
    }
  }
}