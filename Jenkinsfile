pipeline {
  agent any
  stages {
    stage('Hello World') {
      agent any
      steps {
        sh '''pipeline {
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