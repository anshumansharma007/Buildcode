pipeline {
    agent any
    stages {
        stage('build') {

            steps {
                echo 'Hello we are building world'
            }
        }

        stages {
            stage ('test') {

                steps {
                    echo 'testing is completed'
                }
            }

            stages {
                stage ('deploy') {

                    steps {
                        echo 'deployment is completed'
                    }
                }
            }
        }
