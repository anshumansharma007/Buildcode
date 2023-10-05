pipeline {
     agent any 
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
                    withgradle() {
                        sh'./gradlew -v'
                    }
               }
          } 
     }
}


