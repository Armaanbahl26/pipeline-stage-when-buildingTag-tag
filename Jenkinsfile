pipeline{
    agent any
    stages{
        stage("Build Tag"){
            when{
                buildingTag()
            }
            steps{
                echo "Hello World Building Tag"
            }
        }
    }
}
