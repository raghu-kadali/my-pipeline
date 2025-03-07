pipeline {
    Agent any
    stages {
        stage ('Build'){
            steps {
                echo "******** Buiding the application"
            }

        }
        stage ('Sonar') {
            steps {
                echo "*********scanning the application"
            }
        }
        stage ('Docker') {
            steps {
                echo "***********buld the docker image "
            }
        }

        
    }
}
