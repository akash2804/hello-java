pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, this is Zulaikha from edureka'
                     sh 'mkdir akash'
                 }
                 }
                 stage('Integration test') {
                              agent {
                                    docker {
                                            image 'nginx'
                                           }
                              }
                                    }
         }
}
