
node{
	stage('som Checkout'){
		def mvnHome=tool name: 'maven3', type: 'maven'
		
		git 'https://github.com/javahometech/my-app'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
