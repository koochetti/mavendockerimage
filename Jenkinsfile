pipeline {
    agent {
    docker {
        image 'maven:latest'
    }
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
                }
          }

        
   }
}
