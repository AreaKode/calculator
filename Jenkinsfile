pipeline {
	agent any
	stages {
		stage( "Compile" ) {
			steps {
				sh "./mvnw compile"
				sh "./mvnw clean install"
			}
		}
		stage( "Test" ) {
			steps {
				sh "./mvnw clean test"
			}
		}
	}
}
