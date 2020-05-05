pipeline {
    agent any
    stages{
        stage("one") {
            steps{
                script{
                    try{
                        method2()
                    }catch(exc){
                        echo "fails"
                    }
                }
            }
        }
    }
}