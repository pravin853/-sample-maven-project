pipeline {
    agent any 
    tools {
        maven 'maven3'
    }

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
