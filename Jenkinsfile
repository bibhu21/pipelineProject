node{
  stage('Checkout'){
       git 'https://github.com/bibhu21/pipelineProject.git'
  }
  stage('build'){
    app = docker.build("/Users/ibibz/Desktop/coinmarketcap/hello.py")
  }
}
