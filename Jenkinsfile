pipeline { (1)
agent any  (2)
stages {
         stage("Prepare"){ (3)
       steps{
         sh '''
           echo "Prepare continuous delivery env"
           '''
         }
     }

     stage ("Build"){
       steps {
         sh '''
           echo "Building app"
         '''
       }
     }
}
