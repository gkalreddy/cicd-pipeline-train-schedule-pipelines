  pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
               cho 'Running Build Automation'
                sh'./gradlew build --no-daemon'
                archiveArtifacts artifacts:'dist/trainSchedule.zip'
            }
        }
    }
  }

