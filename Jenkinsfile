node {
 	stage('Git') {
		git 'https://github.com/satishchennu1/nodejspipeline.git'
	}
	stage('Build') {
		sh 'npm install'
	}
	stage('Test') {
		sh 'npm test'
	}
    
}
