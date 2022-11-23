pipeline {
    agent {
        label 'agent2'
    }
    environment {
        // AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        // AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
        ENV_VAR1 = 'env_var1_value'
    }
    stages {
        stage('Example stage 1') {
            steps {
                echo 'stage 1..'
                echo "$ENV_VAR1"
                echo '$ENV_VAR1'
            }
        }
        stage('Example stage 2') {
            steps {
                echo 'stage 2..'
            }
        }
    }
}
