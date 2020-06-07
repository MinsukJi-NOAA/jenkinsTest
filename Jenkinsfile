pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            sh 'echo Hello World'
            sh '''
                echo $(hostname)
                echo $(pwd)
                '''
         }
      }
   }
}
