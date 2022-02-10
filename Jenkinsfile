pipeline {
    agent any

    tools {
        jdk 'JAVA'
    }

    options {
        timestamps()
        disableConcurrentBuilds()
    }

    environment {
        JDK_TOOL_VERSION = 'JDK.9.0.4'
        DEVELOP_BRANCH = 'develop'
    }

    stages {
        stage(initialize) {
            steps {
                echo "initialize"
            }
        }

        stage('Build') {
            steps {
                echo "This stage is for Build"
            }
        }

        stage {'Test'} {
            steps {
                echo "This stage is for test"
            }
        }

        stage ('Infrastructure Build') {
            steps {
                echo " This stage is for infrastructure build"
            }
        }

        stage ('Deployment to Staging Env') {
            steps {
                echo "This stage is to deploy into the staging environment"
            }
        }

        stage ('Deployment to Production') {
            steps {
                echo "This stage is to deploy into Production Environment"
            }
        }
            
        
    }

}
