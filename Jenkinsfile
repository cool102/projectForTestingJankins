pipeline
{
agent any

stages
	{
		stage('Build')
		{
		steps {
			bat "maven clean"
		}

		}
		stage('Deploy')
		{
		steps {
		echo 'deploying the code'
		}
		}
		stage('Test')
		{
		steps {
		bat "mvn clean test"
		}
		}
		stage('Unit testing')
		{
		steps {
		bat "mvn compile"
		}
		}
		stage('Release')
		{
		steps {
		echo 'releasing this project'
		}
		}

	}

}