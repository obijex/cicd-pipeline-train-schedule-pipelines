pipeline {
 agent any
  stages {
    stage ('build') {
      steps {
        echo 'running build automation' 
        sh './gradlew build --no-daemon'
        archicheArtifacts artifacts: 'dist/trainSchedule.zip'
      }
      }
  }
}
