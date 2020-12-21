pipeline {
    agent any
    stages {
        stage("Parallel Hello") {
            // run the stages in the parallel block... in parallel, natürlich
            parallel {
                stage("Hello 1") {
                    steps {
                        echo "Hello 1"
                    }
                }
                stage("Hello 2") {
                    steps {
                        echo "Hello 2"
                    }
                }
            }
        }
    }
}
