pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running puneet check build automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
