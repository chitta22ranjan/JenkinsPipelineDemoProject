pipeline{
	agent any
	tools {
        // Install the Maven version configured as "M3" and add it to the path.
       mvn "MAVEN 3.9.0"
    }
	stages {
		stage('Build') 
		{
			steps{
				echo "Building the Code.........."
				mvn clean
			}
		}
		stage('Test') 	{
			steps{
				echo "Testing the Code.........."
				mvn test"
			}
		}
		stage('Compile') 	{
			steps{
				echo "Compiling the Project.........."
				mvn compile
			}
		}
		stage('Deploy') 
			{
			steps{
				echo "Deploying the Project.........."
			}
		}
	}
}
