pipeline {
  agent any
   stages{
     stage('one')
      {
         steps
         {
              addShortText background: '', borderColor: '', color: '', link: '', text: 'ONE'
               sh '''
               echo hello1
               echo hello2
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
