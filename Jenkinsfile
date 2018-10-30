node()
{
  stage('get log')
  {
    echo "123"
    logSteps = currentBuild.getRawBuild().getLog(100)
    logSteps.each
    {
      echo '${it}'
    }
  }
}
