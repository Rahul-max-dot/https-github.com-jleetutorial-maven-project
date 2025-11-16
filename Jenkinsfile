pipeline {
agent any 

  tool {
    maven 'maven_01'
  }

  stages {

    stage (build stage){
      steps{
        bat 'mvn clean install package '
      }
    }
  }
  
}
