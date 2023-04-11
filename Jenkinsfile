pipeline{
  
    agent: any
  
    stages{
        stage('checkout')
        {
            steps{
                git 'https://github.com/zaid-coder-01/React-MusicZone.git'
            }
          
        }
         stage('build')
        {
          steps{
              sh 'docker-compose up'
          }
        }
    }
}
