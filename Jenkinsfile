pipeline
{
  agent any
  stages
  {
    stage('excuting command')
    {
      steps
      {
        sh 'touch abc.txt'
        sh 'eho $JAVA_HOME'
        sh 'eho $MAVEN_HOME'
      }
    }
  }
}
