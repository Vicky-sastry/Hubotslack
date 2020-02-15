pipeline {
  agent any {
  environment {
    MAIN_BRANCH = 'master'
    BUILD_DIR = '/home/jenkins/workspace/{JOB_NAME}/hubot'
    
  stages {
    stage('cf login') {
      steps {
        
          
    
  post {
   
    }
    success {
      slack notify: true, color: 'GREEN', message:  '$BRANCH_NAME $BUILD_DISPLAY_NAME -  Job Built' 
    }
    failure {
      slack notify: true, color: 'RED', message:  '$BRANCH_NAME $BUILD_DISPLAY_NAME - Job failed!'  
    }
  }
}
      
