pipeline {
    agent any

        stages {
            stage ('Initialize'){
                steps{
                    echo "Este es el inicio"
                }
            }
            stage('Build'){
                steps{
                    sh 'mvn -B package'
                }
            }
        }
}
