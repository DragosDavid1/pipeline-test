pipeline {
   agent {
     label "master-piece"
   }
   stages {
     stage('echo') {
       steps {
         echo "say hi!"
       }
      }
     stage('after') {
        echo "stage 2 after stage 1"
      }
   }
}
