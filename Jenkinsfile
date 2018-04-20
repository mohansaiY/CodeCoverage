pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'mvn install'
            }
        }
        stage('Test'){
            steps{
                echo "This is testig phase"
            }
        }
    }
}
