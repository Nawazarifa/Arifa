node {

    stage('Gitclone') {
	
	    git branch: 'main', credentialsId: 'ff544294-e567-4214-b8f4-93372c475862', url: 'https://github.com/Nawazarifa/Arifa.git'
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
		  
		  
