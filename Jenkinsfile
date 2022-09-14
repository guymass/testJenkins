pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {

        
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'maven3', mavenSettingsConfig: 'null') {
            // some block
            sh 'mvn clean install'
        }
      }
    }

  }
    

}
