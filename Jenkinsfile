pipeline {
    agent any
    stages {
        stage ('build'){
            steps {
                echo 'run the building proccess'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
