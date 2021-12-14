pipeline {
    agent any

    stages {
        stage('Build with Packer') {
            steps {
                echo 'Building with Packer........'
            }
        }
        stage('Deploy second asg') {
            steps {
                echo 'Deploying second asg..'
            }
        }
        stage('Switch asg') {
            steps {
                echo 'Switching asg..'
            }
        }
    }
}
