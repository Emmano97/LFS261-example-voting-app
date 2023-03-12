pipeline{
    agent any
    stages{
        stage("one"){
            steps{
                echo "Stage one"
                sleep 5
            }
        }
        stage("two"){
            steps{
                echo "Stage two"
                sleep 7
            }
        }
        stage("three"){
            steps{
                echo "Stage three"
                sleep 9
            }
        }
    }
    post{
        always{
            echo "Pipeline completed"
        }
    }
}