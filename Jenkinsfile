pipeline {
	agent any
	stages {
	 stage ('Compile Stage') {
		  steps {
		withMaven(maven : 'maven_3_5_0') {
		   echo 'mvn clean compile'
	}
    }
}
}
