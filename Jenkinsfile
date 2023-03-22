pipeline {
    agent none
    parameters {
        string(name: 'IME', defaultValue: 'Gospodin iz GIT-a', description: 'Please tell me your name?')
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
            }
        }
    }
}
