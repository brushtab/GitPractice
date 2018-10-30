node()
{
  stage('get log')
  {
    echo "123"
    sleep 5
    logSteps = currentBuild.getRawBuild().getLog(1)
    for (item in logSteps)
    {
      echo item
    }
  }
}
