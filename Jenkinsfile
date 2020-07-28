pipeline {
agent any
   triggers {
      pollSCM('* * * * *') 
   }
stages{
   stage('Build'){
          steps {
             echo 'we r in building stage'
             }
             }
             
    stage('Test'){
        steps{
            echo 'we r in testing stage'
    }
}
   stage('Deploy'{
      steps{
         echo 'Deployment stage'
}
}
         }
         }
