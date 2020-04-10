node{

  stage('Git pull'){
    git 'https://github.com/Rahul-Raj-Singh/jenkins-hello'
    }
    
   stage('Build-Package'){
    def mvnHome = tool name: 'MAVEN3.3', type: 'maven'
    sh "${mvnHome}/bin/mvn clean install"
   }
   
 }
