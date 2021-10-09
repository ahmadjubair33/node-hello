pipeline{
  agent any
  tools { nodejs "Node"}
  stages {
   stage ('build'){
     steps{
         sh 'npm install'
         sh 'npm pack'
         sh "weleecome"
      }
    }
 }
}

