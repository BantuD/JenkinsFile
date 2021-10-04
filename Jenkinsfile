pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      
          stage('Stage 3')
            {
          steps{ echo 'Stage 3'}         
            }
        stage('Clean goad')
        {
            steps { mvn clean}
        }
        stage('Stage 4'){
          steps{
         echo 'Stage4'
          }         
      }
    }
}
