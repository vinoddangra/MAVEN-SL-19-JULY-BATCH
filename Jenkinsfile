pipeline
{
	agent any
	tools
	{
		maven 'MAVEN_HOME'
	}
	
	stages
	{
		stage('Welcome Stage')
		{
			steps
			{
				echo 'Welcome to Jenkins Pipeline'
			}
		}
		
		stage('Clean Stage')
		{
			steps
			{
				sh 'mvn clean'
			}
		}
		stage('Build Stage')
		{
			steps
			{
				sh 'mvn package'
			}
		}		
		
		stage('Build Success')
		{
			steps
			{
				echo 'Build successful'
			}
		}
		
	}
}	