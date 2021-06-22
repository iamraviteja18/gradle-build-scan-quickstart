pipeline {
  agent {
        docker {
            image 'gradle:3-alpine'
        }
    }
  stages {
   stage('Build'){
     steps{
       sh './gradlew build --scan'
     }
    }
 }
}
