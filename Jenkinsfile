pipeline{
  agent any
  stages {
    stage ('Build') {
      steps{
        echo 'Running Build Automation'
        sh './gradlew build' --no-daemon
        archiveArtifact artifacts:'dis/trainSchedule.zip
      }
    }
  {
}
