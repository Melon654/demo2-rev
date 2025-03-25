pipeline
{
  agent any
  stages
  {
    stage("cloning")
    {
      steps
      {
        git url
      }
    }
    stage("build")
    {
      steps
      {
        sh "javac write.java"
      }
    }
    stage("run"}
          {
            steps
            {
              sh "java write"
            }
          }
          }
          }
