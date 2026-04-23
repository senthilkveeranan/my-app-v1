node {
  stage('SCM Checkout'){
    git 'https://github.com/senthilkveeranan/my-app-v1.git'
  }
  stage('Compile a package'){
    sh 'mvn clean package'
  }
}
