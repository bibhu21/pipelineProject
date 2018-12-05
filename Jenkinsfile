node{
  stage('Checkout'){
       git 'https://github.com/bibhu21/pipelineProject.git'
  }
  stage('mvn package'){
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"  }
}
