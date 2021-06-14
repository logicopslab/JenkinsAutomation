pipeline {
    agent any

    stages {
        stage('FirstBatch') {
            steps {
                bat First.bat
            }
        }
        stage('SecondBatch') {
            steps {
                bat Second.bat
            }
        }
    }
}
