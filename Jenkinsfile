pipeline {
    agent any 
   // agent { 
   //    label 'Scipt_Slave' 
   // }
    stages {
        stage (GitCheckout) {
            steps {
                git branch: 'J2EE', url: 'git@github.com:VTechnologies-NagireddyVenna/onlinebookstore.git'
            }
        }
    }
}

