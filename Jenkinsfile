pipeline{
    agent any
    triggers{
      cron('* * * * *')
    }
  stages{
    stage("flask"){
      steps{
        bat 'python main.py'
      }
    }
  }
}
