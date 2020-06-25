pipeline {
   agent any

   stages {
      stage('Print Hello and hostname') {
         steps {
            echo 'Hello World'
            sh 'hostname'
         }
      }
      stage ('Check OS type and version '){
          steps {
              echo 'print file os-release'
              sh 'cat /etc/os-release'
          }
      }
      stage ('Execute code'){
          steps{
              echo 'excecute app code'
              sh 'superJulyCode.txt'
          }
      }
   }
}
