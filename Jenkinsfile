pipeline {
      agent { label 'jenkins-slave1-do' }
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Anshul from Krishna Bommana'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
