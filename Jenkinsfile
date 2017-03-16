@Library("yooture@test")
import org.foo.Zot

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
                echo "DEBUGGING WITH CHANGES again asldkjadlksasdkljj"
            }
        }
    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }
}
