pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''tardis {
   agent any
    
   stages {
      stage(\'Say Hello\') {
         steps {
            echo \'Hello World!\'   
         }
      }
   }
}'''
        }
      }
    }
  }