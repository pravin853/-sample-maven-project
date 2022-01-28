pipeline {
    agent any 
    stages {
     stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'null', mavenSettingsConfig: 'null') {
    sh 'maven clean install'
     }
    }
  }

}

}
