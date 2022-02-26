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
        touch test.txt
      }
   }
}
