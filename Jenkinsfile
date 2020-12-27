pipeline {
    agent any
    stages {
            stage ("Starting Squish Server"){
            steps{
            echo 'Squish Server started'}
            }
        
        stage ("Execute Scripts"){
            steps{
            dir("C:/Users/gih5kor/Squish for Windows 6.4.3_2/bin"){
                bat "jenkins_start_execution.bat"
            }
            }
        }
        
        stage ("Stop Squish Server"){
            steps{
            dir("C:/Users/gih5kor/Squish for Windows 6.4.3_2/bin"){
                bat "jenkins_stop_Squish_server.bat"
            }
            }
        }
    }
}

