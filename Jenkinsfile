pipeline{
  agent any

  stages{
    stage('Build'){
      steps{
	echo "Building"
      }
    }
  }
  stages{
    stage('Testing'){
      steps{
        echo "Running Unit Test"
      }
    }
  }
  stages{
    stage('Publish'){
      steps{
	echo "Publishing artifact"
      } 
    }
  }
}
