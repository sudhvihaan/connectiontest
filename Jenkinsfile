pipeline {
    agent {
        label 'jenkins-slave' // This is the agent used for the pipeline
    }

    stages {
        stage('clone_test') {
            steps {
                echo 'Cloning repository...'
                // Using credentialsId to pass SSH credentials
                git url: 'git@github.com:sudhvihaan/connectiontest.git', 
                    branch: 'main',
                    credentialsId: 'vault-ssh-pvt-key-github'
            }
        }
    }
}

