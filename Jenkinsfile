pipeline {

    agent any

    stages {

        stage ("Build"){

            steps {
                sh "./mvwn install"
            }
        }
        stage ( "run test") {

            steps {
                sh "./mvwn test"
            }
        }
    }
}