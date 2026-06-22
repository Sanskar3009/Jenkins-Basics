pipeline {
   agent any // Runs on any available agent
   stages {
       stage('Build') {
           steps {
               echo 'Building the project...'
               sh 'mvn clean install'
           }
       }
       stage('Test') {
           steps {
               echo 'Running tests...'
              
           }
       }
       stage('Deploy') {
           steps {
               echo 'Deploying the application...'
               
           }
       }
   }
   post {
       always {
           echo 'Pipeline execution completed.'
       }
   }
}
