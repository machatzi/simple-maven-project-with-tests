pipeline {
  agent any
  stages {
    stage('TEST') {
      steps {
        echo '"Hello"'
      }
    }
    stage('Install') {
      steps {
        bat '"C:\\\\apache-maven-3.3.9\\\\bin\\\\mvn.cmd" install'
      }
    }
  }
}