pipeline {
    agent linux 
    stages {
    stage('maven install') {
      steps {

        
        withMaven(maven: 'maven3') {
            // some block
            sh 'mvn clean install'
        }
      }
    }

  }
    

}
