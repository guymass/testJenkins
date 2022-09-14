pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {

        
        withMaven {
            sh 'mvn clean install'
    }

      }
    }

  }
    
        stages {
  stage('build') {
    steps {
        echo 'Building pipeline...'
    }
  }

  stage('test') {
    steps {
        echo 'Testing pipeline ...'
    }
  }

  stage('deploy') {
    steps {
        echo 'Deploying pipeline ...'
        echo 'Done!'
    }
  }


}
