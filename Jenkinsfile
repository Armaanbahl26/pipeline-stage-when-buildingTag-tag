pipeline{
    agent any
    stages{
        stage("Build Tag"){
            when{
                // buildingTag()
                tag "2.0"
            }
            steps{
                echo "Hello World Building Tag"
            }
        }
    }
}
