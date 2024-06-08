pipeline{
    agent any
    stages{
        stage('Fetch Code'){
            steps{
                git branch:'main', url:'https://github.com/Mustakim4/jenkins-python.git'
            }
        }
        
        stage('Build'){
            steps{
                sh 'python3 first.py'
            }

	    steps{
	    	sh 'echo "success"'
	    }
        }
    }
}
