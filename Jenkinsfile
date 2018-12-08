node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
      def mvnhome = tool name: '', type: 'maven'   
      bash "${mvnhome}/bin/mvn package"
   }
}