pipeline{
    agent any
    stage{
        stage("build"){
            when{
                expression{
                    BRANCH_NAME=='master'
                }
            }
            
            steps{
                echo "hello world"
            }
        }
        stage("test"){
            steps{
                echo "test part"
            }
        }
        stage("deployee"){
            steps{
                echo "deployee"
            }
        }
    }
}
