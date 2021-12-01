pipeline
{
  agent any
  stages
  {
    stage ('executing command')
    {
      steps
      {
        sh 'touch abc.txt'
        sh 'echo $JAVA_HOME'
        sh 'echo $MAVEN_HOME'
      }
    }
  }
}
