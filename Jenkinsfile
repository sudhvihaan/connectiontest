pipeline {
    agent {
        label 'jenkins-slave' // This is the agent used for the pipeline
    }

    stages {
        stage('clone_test') {
            steps {
                echo 'Cloning repository...'
                // Using a shell command to clone the repository
                sh 'git@github.com:sudhvihaan/core-pipeline.git'
                 
            }
        }
    }
}
