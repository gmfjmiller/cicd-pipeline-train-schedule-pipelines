pipeline {
  agend any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build Automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts archive: 'dist/trainSchedule.zip'
      }
    }
  }
}
