pipeline {
    agent any

    stages {
        stage ("Hello") {
            steps {
                echo "Hello World"
            }
        }

        stage ("Test") {
            when { branch "PR-*" }
            steps {
                sh """
                echo 'Fallando los test'
                exit 1
                """
            }
        }
    }
}
