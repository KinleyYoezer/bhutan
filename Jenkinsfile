pipeline
{
  agent any
    stages{
      stage ('Git pull'){
        steps{
          sh 'git pull origin master'
        }
        }
      stage('Display Content'){
        steps{
          sh 'cat file1'
        }
      }
    }
}
