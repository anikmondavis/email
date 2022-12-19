pipeline{
    agent any
    stages{
        stage("build"){
            when{
                expression{
                    env.BRANCH_NAME.startsWith('PR')
                }
            }
            
            steps{
                echo "This is when pr was rasied"
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
