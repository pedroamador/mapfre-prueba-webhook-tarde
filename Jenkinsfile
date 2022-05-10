pipeline {
    agent any

    stages {
        stage ("Hello") {
            steps {
                echo "Hello World"
            }
        }

        stage ("A cotillear el disco") {
            steps {
                sh """
                hostname
                pwd
                ls -la
                """
            }
        }
        stage ("A dormir un rato") {
            steps {
                sh "sleep 60"
            }
        }
    }
}
