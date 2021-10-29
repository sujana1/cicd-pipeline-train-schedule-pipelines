pipeline {
  agent any 
    stages{
      stage ('build')
      {
        steps{
          echo 'Running build automation'
          sh './gradlew build --no-demeon'
          archiveArifacts artifacts: 'dist/trainschedule.zip'
        }
      }
    }
}
