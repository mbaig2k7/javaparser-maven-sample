pipeline {
  agent any
     tools { 
        maven 'MAVEN' 
        }
    stages{
        stage("mvn build") {
            steps {
                    sh 'mvn --debug clean package'
         
                }
                }
       post {
              
        failure {
            mail to: mbaig2k7@gmail.com, subject: 'The Pipeline failed :('
        }
            }
            }

