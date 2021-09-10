pipeline{
    agent any
    stages{
        stage('Build')
        {
            steps{
                echo 'Build successfully'
         
            }
        }
        stage('git')
         {
             steps{
                 git 'https://github.com/Meghana-28/MavenCounterWebApp.git'
             }
         }
         stage('test')
         {
            steps{
                echo 'tested successsfully'
            }    
         }
         stage('deploy')
         {
             steps
             {
                  echo 'deployed successsfully'
             }
         }
    }
}
