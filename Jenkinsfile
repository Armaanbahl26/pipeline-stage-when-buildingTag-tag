pipeline{
    agent any
    stages{
        stage("Build Tag"){
            when{
                // buildingTag()
                tag "release-*"
            }
            steps{
                echo "Hello World Building Tag"
            }
        }
    }
}
