pipeline
  { 
   agent any
    stages { 
        stage('Checkout'){
          steps {
            checkout scm
              }}
          
         stage('Build') {
          steps 
          {
            sh '/home/aksh/Documents/Devops/apache-maven-3.9.1/bin/mvn install'
              }  
                }
              stage('Deployment')
                {
                  step
                    {
                      sh 'cp target/box1.war /home/aksh/Documents/Devops/apache-tomcat-9.0.73/webapps'
                      }
                        }
                          }
                            }
