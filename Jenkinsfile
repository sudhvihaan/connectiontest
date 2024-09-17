pipeline {
    agent {
        label 'testultimate' // This is the agent used for the pipeline
    }

    stages {
        stage('clone_test') {
            steps {
                echo 'Cloning repository...'
                git url: 'https://github.com/sudhvihaan/djangoApp1.git', branch: 'main'
            }
        }
    }
}

