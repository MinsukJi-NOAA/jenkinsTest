pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            sh 'echo Hello World 3'
            sh '''
                echo $(hostname)
                echo $(pwd)
                echo $(whoami)
                echo $(date)
                echo $(which docker)
                echo ${USER}
                '''
         }
      }
   }
}
