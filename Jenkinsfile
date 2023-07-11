pipeline {
  agent {
       label {
           label "built-in"
       }
  }
        stages {
             stage ('23Q1-deploy') {
                     steps {
                       sh "cp -r /mnt/vel-app2/index.html /var/www/ 
                     }
             }
        }
  
}
