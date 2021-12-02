node {
	stage ('SCM checkout'){
		git "https://github.com/Alkayde/JenkinsFirstTest.git"
		}
	stage ('Build'){
       	dir("out/artifacts/JenkinsFirstTest_jar") {
	   sh "java -jar JenkinsFirstTest.jar"
       }
		}
}
