node{
  stage('SCM Checkout'){
  git 'https://github.com/sathiyabalaji/MobileAuto'
  }
  stage('Compile-Package'){
  def mvnHome=tool name: 'Maven 3.6.3', type: 'maven'  
  sh "${mvnHome}/bin/mvn package"
  }
}
