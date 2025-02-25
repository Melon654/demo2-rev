pipeline 
{
agent any
stages
{
stage('clone')
{
steps
{
git "https://github.com/Melon654/demo2-rev.git"
}
}
  stage('build')
  {
    steps
    {
      sh 'javac write.java'
    }
  }
  stage('run')
  {
    steps
    {
      sh 'java write'
    }
  }
}
}

