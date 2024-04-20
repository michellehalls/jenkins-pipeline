pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo "fetch the source code from the directory path specified by the environment variable"
                echo "compile the code and generate any necessary artifacts"
            }
        }
        stage("Unit and Integration Tests") {
            steps {
                echo "unit tests"
                echo "integration tests"
            }
        }
        stage("Code Analysis") {
            steps {
                echo "check the quality of the code"
            }
        }
        stage("Security Scan") {
            steps {
                echo "deploy the application to a testing environment specified by the environment variable named "
            }
        }
        stage("Deploy to Staging") {
            steps {
                sleep time: 10, unit: 'SECONDS'
            }
        }
        stage("Integration Tests on Staging") {
            steps {
                echo "deploying the code to the production environmentT"
            }
        }
        stage("Deploy to Production"){
            steps{
                echo "steps for Deploy to production"
            }
        }
    }
}
