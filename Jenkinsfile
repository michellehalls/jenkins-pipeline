pipeline{
    agent{
        label "node"
    }
    stages{
        stage("Build"){
            steps{
                echo "========executing Build========"
            }
        stage("Test"){
            steps{
                echo "========executing test========"
            }
            post{
                success{
                    echo "=======test executed successfully========"
                }
            }
        }
    }
    post{
        always{
            echo "========always pipeline - sending email========"
        }
    }
}
}
