#!groovy

node {
	   
	stage('Checkout'){
	git credentialsId: '165e8383-9d20-4fe9-94f2-7840bc763c7a', url: 'https://github.com/bhagyaraj12345/Maven-Web-Project.git'

         // checkout scm
       }

       stage('BuildArtifact'){

         // sh 'mvn install'
	       
	       sh 'mvn clean'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                   // sh 'mvn sonar:sonar'
                }
       
}
