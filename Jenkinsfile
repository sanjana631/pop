pipeline{
  agent any
  stages{
    stage('Comile java program'){
      steps {
        bat 'javac HelloWorld.java'
      }
    }
    stage('Run Java program'){
      steps {
        bat 'java HelloWorld'
      }
    }
  }
}
