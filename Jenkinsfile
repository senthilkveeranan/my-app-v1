node {
  stage('SCM Checkout'){
    git 'https://github.com/senthilkveeranan/my-app-v1.git'
  }
  stage('Compile a package'){
    dev mvnHome = tool name: 'Maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package'
  }
}
