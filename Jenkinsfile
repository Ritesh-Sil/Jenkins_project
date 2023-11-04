pipeline{
  agent any
  stages{
    stage("First Step"){
      steps{
        echo "This is the first step"
      }
    }
    stage("Second Step"){
      steps{
        echo "This is the second step"
      }
    }
    stage("Run the python script"){
      steps{
        sh "python3 /src/helloWorld.py"
      }
    }
  }
}
