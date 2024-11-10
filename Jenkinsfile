pipeline {
    agent any 
   // agent { 
   //    label 'Scipt_Slave' 
   // }
    stages {
        stage (GitCheckout) {
            steps {
                git branch: 'J2EE', url: 'https://github.com/VTechnologies-NagireddyVenna/onlinebookstore.git'
            }
        }
    }
}

