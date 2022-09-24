pipeline {
    agent any
    stages {
     stage("clone") {
         steps {
           git 'https://github.com/janchel/ansible-project.git'
         }
     }
     stage("build") {
         steps {
             sh 'pwd'
         }
     }
     stage("test") {
         steps {
             sh 'ls -ltarh'
         }
     }
    }

}
