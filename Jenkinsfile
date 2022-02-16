pipeline{
  agent any
  stages{
    stage ('Echo parametes'){
      steps{
        echo(GITHUB_URL)
        echo(TARGET_BRANCH)
        echo(SONAR_URL)
      }
    }
  }
}
