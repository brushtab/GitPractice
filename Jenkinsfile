node()
{
  stage('get log')
  {
    echo "Doing job"
    echo "Ready to run"
    echo "MSK TIME is 10:00"
    echo "MSK TIME is 10:01"
    echo "MSK TIME is 10:02"
    echo "Started run"
    echo "Run Id is 1090"
    echo "RunId is 1090"
    echo "Doing Load Test"
    echo "LADLOADLASODLAODLA"
    echo "This was LOAD BRO"
    echo "Finished run 1090"
    echo "Run Id is 1090"
    sleep 5
    logSteps = currentBuild.getRawBuild().getLog(3)
    for (item in logSteps)
    {
      if (item.contains("Run Id"))
      {
        echo item
      }
    }
  }
}
