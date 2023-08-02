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
        stage("Docker") {
            steps {
                    sh 'docker build .'
         
                }
                }
       
            }
}

