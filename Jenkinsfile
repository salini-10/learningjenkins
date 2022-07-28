pipeline {
  agent any
   stages{
     stage('one')
      {
         steps
         {
              addBadge icon: '', id: '', link: '', text: 'ONE'
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
