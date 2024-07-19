pipeline{
agent any

stages{
    stage(setup){
        steps{
            bat docker-compose up
        }
    }
     stage(tear){
        steps{
            bat docker-down
        }
    }
}


}