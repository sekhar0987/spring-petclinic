pipeline {

    agent any

    stages {

        stage ("Build"){

            steps {
                sh "./mvwn install"
            }
        }
        stage ( "Run unit test") {

            steps {
                sh "./mvwn test"
            }
        }
    }
}