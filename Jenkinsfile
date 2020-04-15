pipeline{
 agent any
 stages{
  stage(hello){
       steps{
       echo "helloo"
       }
      }
  stage(build){
       steps{
         sh label: '', script: 'mvn clean install package deploy'
       }
      }
    }
  }
