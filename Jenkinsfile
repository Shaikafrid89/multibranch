pipeline{
   agent any
    stages{
        stage("maven muild"){
            when{
                baranch "develop"
                steps{
                sh "mvn package"
                }
        }
    }
}
