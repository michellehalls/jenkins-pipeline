pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Build"){
            steps{
                echo "========executing Build========"
            }
            post{
                success{
                    echo "========build executed successfully========"
                }
            }
        }
    }
    post{
        always{
            echo "========always pipeline========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
