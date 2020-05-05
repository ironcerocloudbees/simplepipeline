pipeline {
    node {
        stage("one") {
            steps{
         
                try{
                    method2()
                }catch(exc){
                    echo "fails"
                }
        
            }
        }
    }
}