pipeline {
  agent any 
    stages{
      stage ('build')
      {
        steps{
          echo 'Running build automation'
          sh './gradlew build '
          archiveArifacts artifacts: 'dist/trainschedule.zip'
        }
      }
    }
}
