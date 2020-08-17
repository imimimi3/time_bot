String repoUrl = "https://github.com/imimimi3/time_bot.git"

node {
  stage('Clone') {
      echo 'Make the output directory'
      sh 'mkdir -p /var/gitbot1'
      
      dir('build') {
           url: repoUrl
      }     
  }       
}
