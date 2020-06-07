pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            sh 'echo Hello World 2'
            sh '''
                echo $(hostname)
                echo $(pwd)
                '''
         }
      }
   }
}
