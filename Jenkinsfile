pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				sh ''' 
				   echo "This is the Build stage"
				   sleep 2  
				'''
			}
	}
		stage('Test'){
			steps{
				sh ''' 
				echo "This is the Test stage"
				sleep 2
				'''
			}
		}
		stage('Deploy'){
			steps{
				sh ''' 
				echo "This is the Deploy stage"
				sleep 2
				'''
			}
		}
}
