pipeline {
  // This is a Jenkinsfile, it's read and parsed by Jenkins to determine how it should build, test and deploy your code

  // The first thing we'll need is an agent
  // An agent is a node defined within Jenkins (it can be hosted internally or externally) but think of it as a runtime environment for your code
  agent any

  // Stages are the next most important thing and they define all of the steps that need to occur inside this pipeline
  stages{
    // Inside of here I can define all of the stages that need to occur (in order) to complete the pipeline
    // If any stage fails for whatever reason the code stops and it doesn't continue to further stages
    stage('Build'){
      // Within each stage is a list of steps that need to occur to execute this stage
      steps{
        sh 'echo "Build Stage Started"'
      }
    }
    stage('Test'){
      steps{
        sh 'echo "Test Stage Started"'
      }
    }
    stage('Deploy'){
      steps{
        sh 'echo "Deploy Stage Started"'
      }
    }
  }
}
