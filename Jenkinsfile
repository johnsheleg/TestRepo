pipeline {
  agent any
  stages {
    stage('Sleep 5') {
      steps {
        parallel(
          "Sleep 5": {
            sleep 5
            
          },
          "Sleep 6": {
            sleep 6
            
          },
          "Sleep 10": {
            sleep 10
            
          }
        )
      }
    }
    stage('Sleep4') {
      steps {
        parallel(
          "Sleep4": {
            sleep 4
            
          },
          "Sleep 6": {
            sleep 6
            
          }
        )
      }
    }
  }
}