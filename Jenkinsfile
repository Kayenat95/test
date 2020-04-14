pipeline{
       agent any
       stage{
             stage("Cleaning stage"){
                   steps{
        bat "mvn clean"
        }
    }
        stage("Testing stage"){
                   steps{
        bat "mvn test"
        }
    }
        stage("Packaging stage"){
                   steps{
        bat "mvn test"
        }
    }  
 }
}      
