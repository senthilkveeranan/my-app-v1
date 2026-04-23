node {
  stage('SCM Checkout'){
    git 'https://github.com/senthilkveeranan/my-app-v1.git'
  }
  stage('Compile a package'){
    sh '/opt/maven-3.9.15/bin/mvn clean package'
  }
}
