pipeline {
agent any
tools {
    gradle 'Gradle_version '
    maven  'M3 '
    jdk    'JDK12.0'
}
stages{
   stage('Build'){
          steps {
             sh 'mvn -v'
             }
             }
             }
    stage('Test'){
        steps 'echo we r in testing stage'
    }
}
