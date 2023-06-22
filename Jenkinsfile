pipeline {
  agent any
     tools { 
        maven 'MAVEN' 
        }
    stages{
        stage("mvn build") {
            steps {
                    sh 'mvn -X clean package'
         
                }
                }
            }
            }
