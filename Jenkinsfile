pipeline {
  agent {
       label {
           label "built-in"
       }
  }
        stages {
             stage ('23Q2-deploy') {
                     steps {
                       sh "cp -r /mnt/vel-app2/index.html /var/www/html/"
                       sh "chmod -R 777 /var/www/html/index.html"
                     }
             }
        }
  
}
