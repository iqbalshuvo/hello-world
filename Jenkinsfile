pipeline{

agent any
stages{
   stage('build'){
       steps {
           
           sh 'mvn clean package'
       }
   }
   stage('install'){
       steps{
           sh 'mvn clean install'
       }
   } 
 
}
}
