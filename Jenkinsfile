pipeline{
    agent any
    stages{
        stage('Build'){
			steps{
			    timestamps { 
					echo "Hello World in Build"
					echo "Hello World in Build Again"
				}
			}
        }
		
        stage('Test'){
            steps{
                echo "Hello World in Test"
                echo "Hello World in Test Again"
            }
        }		
    }
}
