node {

    stage('Gitclone') {
	
	  git branch: 'main', credentialsId: '6c0499f4-7c6b-4de2-b068-68dd6cf1c3f6', url: 'https://github.com/Nawazarifa/Arifa.git'
    }
	stage('java version') {
	
	       sh 'java -version'
    }
	stage('maven version') {
	
	      sh 'mvn --version'
	}
	stage('maven validate ') {
	
	      sh  'mvn validate'
	}
	stage ('maven compile') {
	
	      sh  'mvn compile'
    }
	stage('maven test')  {
	
	      sh 'mvn test'
	}
	stage('maven package') {
	
	      sh 'mvn package'
	
	}
	stage('maven deploy') {
	
	      sh 'mvn deploy'
	
	}
	

	}
		  
		  
