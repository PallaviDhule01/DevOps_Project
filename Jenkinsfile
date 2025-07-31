pipeline {
    agent any

    parameters {
        string(name: 'GREETING_NAME', defaultValue: 'Pallavi', description: 'pallavi Dhule')
    }

    stages {
        stage('Greet from Main') {
            steps {
                echo "Hello from MASTER branch, ${params.GREETING_NAME}!"
            }
        }
    }
}
