pipeline {
    agent any
    stages {
        stage ('hello') {
            steps {
                echo 'hello world'
            }
       }
        stage ('verify branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
    
    
    }
}
