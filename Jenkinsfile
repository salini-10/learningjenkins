pipeline {
  agent any
  environment {
    ENV_URL = "pipeline.google.com"
    SSH_CRED = credentials("SSH")
   }
   stages{
     stage('one')
      {
         steps
         {
              addShortText background: '', borderColor: '', color: '', link: '', text: 'ONE'
               sh '''
               echo hello1
               echo hello2
               echo ENV_URL = ${ENV_URL}
               '''
           }
    }

     stage('two')
           {
              steps
              {

              echo "two"

           }
         }

   }

  }
