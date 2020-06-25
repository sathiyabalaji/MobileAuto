node{
  stage('SCM Checkout'){
  git 'https://github.com/sathiyabalaji/MobileAuto'
  }
  stage('Compile-Package'){
  //def mvnHome=tool name: 'Maven-3.5.0', type: 'maven'  
  //sh "${mvnHome}/bin/mvn package"
    sh 'mvn package'
  }
}
