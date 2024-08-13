pipeline {
    agent { label 'built-in' } // This specifies the Built-In Node

    stages {
        stage('Checkout Code') { 
            steps {
                git 'https://github.com/maping/java-maven-calculator-web-app.git'
            }
        }
    }
}

