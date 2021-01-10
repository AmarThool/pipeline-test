pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Hi ..this is build engg from build stage..'
            }

        }

        stage('Test') {
            steps {
                echo 'Hi,, this is from the testin stage'
            }
        }

        stage('deploy') {
            steps {
                echo 'hi .. this is from deployment side'
            }
        }
        stage(release) {
            steps {
                echo 'Hi..this is from final steps..'
                echo 'your application is ready for release..'
            }
        }

    
    }

}
