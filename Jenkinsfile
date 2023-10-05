pipeline {
     agent any 
     stages {
          stage ("run frontend"){
               steps {
                    echo 'excuting yarn....'
                    nodejs('nodejs-19.0') {
                        sh'yarn install'
                    }
               }
          } 


      stage ("run frontend"){
               steps {
                    echo 'excuting gradle....'
                    withgradle() {
                        sh'./gradlew -v'
                    }
               }
          } 
     }
}
