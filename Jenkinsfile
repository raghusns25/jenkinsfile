pipeline {
agent any
   triggers {
      pollSCM('0 0/1 0 ? * * *') 
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
}
}
