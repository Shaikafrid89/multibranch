pipeline{
    agent any
    stages{
        stage("maven build"){
            when{
            branch "develop"
                steps{
                echo "welcome to multi branch"
                }
            }
        }
        stage("deploy"){
            when{
            branch "qa"
                steps{
                echo "hello world"
                }
            }
        }
    }
}
