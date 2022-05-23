node{
  stage('SCM Checkout'){
    git 'https://github.com/Anandunakal03/myappln'
    // git 'https://github.com/javahometech/my-app'
  }
  
   stage('Compile-Package'){
     //get maven home path
     def mvnHome = tool name: 'Maven', type: 'maven'
     
     sh "${mvnHome}/bin/mvn package"
     
     
  }
  
}  
