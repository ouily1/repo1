node{
   stage('SCM Checkout'){
     git 'https://github.com/ouily1/repo1'
   }
   stage('Compile-Package'){
      def mvnhome = tool name: 'maven-3', type: 'maven'   
      bash "${mvnhome}/bin/mvn package"
   }
}