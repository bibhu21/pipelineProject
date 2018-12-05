node{
  stage('Checkout'){
       git 'https://github.com/bibhu21/pipelineProject.git'
  }
  stage('mvn package'){
    sh 'mvn clean package'
  }
}
