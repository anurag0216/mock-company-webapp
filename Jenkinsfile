pipeline {
  stages{
          stage('Build'){
                steps{
                   sh './gradlew assemble'
                }
              }
             stage('unit Test'){
                        steps{
                           sh'./gradlew test'
                              }
                           }
                       }

}
