pipeline {
     agent any 

     tools{
          gradle 'Gradle-6.2'
     }
     
     stages {
          stage ("run frontend"){
               steps {
                    echo 'excuting yarn....'
                    nodejs('nodejs-10.17') {
                        sh'yarn install'
                    }
               }
          } 
          stage ("run backend"){
               steps {
                    echo 'excuting gradle....'
                      sh '../gradle -v'
                    }
               }
          } 
     }



