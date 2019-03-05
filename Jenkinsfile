node{
   stage('SCM Checkout'){
      git 'https://github.com/sreekanth31/LoginTemplate'
	}
	stage('Compile-package'){
	   def mvnHome = tool name: 'maven', type: 'maven'
	   sh "${mvnHome}/bin/mvn clean package"
	}
}
