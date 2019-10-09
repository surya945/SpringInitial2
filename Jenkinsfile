node{
	stage('SCM Checkout'){
		git 'https://github.com/surya945/SpringInitial2.git'
	}
	stage('Compile-Package'){
		sh 'mvn clean install'
	}
}