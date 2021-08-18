pipeline{
    agent any
    stages{
        stage('Build Master'){
            when{
                branch 'master'
            }
            steps{
                echo 'Building master'
            }
            
        }
        stage('Build Dxev'){
            when{
                branch 'Dev'
            }
            steps{
                echo 'Building Slave'
            }
            
        }
    }
}
