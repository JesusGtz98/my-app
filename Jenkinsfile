node{
    stage('SCM Checkout'){
      git 'https://github.com/JesusGtz98/my-app'
      }
      stage('Compile-Package'){
      
       def mvnHome = tool name: 'Maven_home', type: 'maven
       sh "${mvnHome}/bin/mvn package"
       }
      
}
