pipeline{

agent any
stages{
    stage ('git'){
    steps {
        git credentialsId: 'git_id', url: 'https://github.com/iqbalshuvo/hello-world.git'
    }
}
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
