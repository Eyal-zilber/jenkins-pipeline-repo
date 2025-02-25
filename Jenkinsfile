pipeline {
    agent any
    stages {
        stage('Create File') {
            steps {
                script {
                    // יצירת קובץ ריק
                    sh 'touch emptyfile.txt'
                }
            }
        }
        stage('Echo') {
            steps {
                script {
                    // הרצת הפקודה echo
                    echo "Hello from Pipeline!"
                }
            }
        }
    }
}
