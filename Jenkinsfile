pipeline {
    agent any
    environment {
        PROJECT_NAME = "MyProject"  // Global variable
    }
    stages {
        stage('Print Name') {
            steps {
                echo "Project Name: ${env.PROJECT_NAME}"  // Access global variable with env.VARIABLE_NAME
            }
        }
    }
}
