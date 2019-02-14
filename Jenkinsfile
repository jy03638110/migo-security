pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'bulid'
        bat 'mvn clean:package'
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
    stage('publish') {
      steps {
        echo 'publish'
      }
    }
    stage('archive') {
      steps {
        echo 'Archive'
      }
    }
  }
}
