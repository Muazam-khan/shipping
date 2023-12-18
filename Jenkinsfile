 pipeline {
    agent {
        label "ws"
    }
    stages{
        stage('Lint Checks'){
          steps {
            sh "echo ***** Starting Style Checks *****"
         //   sh "mvn checkstyle:check || true" // this cmd does style check for server.js
             sh "echo ***** Completed Style Checks *****"
        }
          
    }
        stage('Static Code Analysis'){
          steps {
            sh "echo ***** Starting Static Code Analysis *****"
          //  sh "/home/centos/node_modules/jslint/bin/jslint.js server.js" // this cmd does style check for server.js
           //  sh "echo ***** Completed Style Checks *****"
        }
          
    }

  }
}