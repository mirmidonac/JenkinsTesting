pipeline {
    agent none
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
            }
            steps {
                sh 'mvn --version'
                sh 'java -version'
            }
        }
    }
}
