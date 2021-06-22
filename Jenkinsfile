pipeline {
  agent any
  
  stages{
  stage('Build') {
            steps{
       sh './gradlew build --scan'
     }
        }
        stage('Test') {
            steps {
                sh './gradlew test'
            }
        }
  }
}
