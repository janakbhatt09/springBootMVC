node{
  stage('SCM Checkout'){
 
    git 'https://github.com/janakbhatt09/springBootMVC/new/master'
  }
  stage('Compile-Package'){
    def mvnHome = tool name: '', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }

}
