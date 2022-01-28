pipeline {
    agent any 
    tools { 
        maven 'Maven 3.8.4' 
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
