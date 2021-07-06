pipeline {

  agent any
  
  stages {
    
    stage("build") {
       steps {
         input ('Building the application... Do you wish to proceed to testing phase?')
      }
    }
     stage("test") {
       steps {
         input ('Testing the application... Do you wish to proceed to deploying stage?')
      }
    }
     stage("deploy") {
       steps {
         input ('Deploying the application... Do you wish to proceed and publish the app?')
      }
    }
  }
}
  
