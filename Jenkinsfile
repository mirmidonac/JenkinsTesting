pipeline {
    agent any
    parameters {
        string(name: 'IME', defaultValue: 'Gospodin iz GIT-a')
    }
    stages {
        stage('Prvi STAGE') {
            steps { 
                 echo "Zdravo ${params.IME}"
            }
        }
        stage('Drugi STAGE') {
            steps { 
                echo 'Oh snap you are here'
                sh 'java -version'
            }
        }
        stage('Final STAGE') {
            steps { 
                echo 'End of the rode'
                sh 'node -version'
            }
        }
    }
}
