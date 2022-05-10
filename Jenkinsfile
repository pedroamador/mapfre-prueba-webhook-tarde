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
    }
}
