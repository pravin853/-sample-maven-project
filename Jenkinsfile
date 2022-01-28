pipeline {
    agent any 
    stages {
     stage('maven install') {
    steps {
      withMaven(maven: 'maven3') {
      sh 'maven clean install'
     }
    }
  }

}

}
