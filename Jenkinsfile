pipeline{
       agent any
       stage{
             stage("Cleaning stage"){
                   steps{
        bat "mvn clean"
        }
    }
       stage{
             stage("Testing stage"){
                   steps{
        bat "mvn test"
        }
    }
       stage{
             stage("Packaging stage"){
                   steps{
        bat "mvn test"
        }
    }  
 }
