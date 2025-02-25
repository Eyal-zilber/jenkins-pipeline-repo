pipeline {
    agent any
    stages {
        stage('Create File') {
            steps {
                script {
                    // יצירת קובץ ריק בצורה שתואמת ל-Windows
                    bat 'type nul > emptyfile.txt'
                }
            }
        }
        stage('Echo') {
            steps {
                script {
                    // הדפסת הודעה
                    echo "Hello from Pipeline!"
                }
            }
        }
    }
}
