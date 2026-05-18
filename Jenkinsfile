pipeline{
	agent none
	stages{
		stage('Build'){
			agent : {label 'jenkinsNode1'}
			steps{
				
				sh ''' 
				   echo "This is the Build stage" 
				   sleep 2  
				'''
			}
	}
		stage('Test'){
			agent : {label 'jenkinsNode2'}
			steps{
				sh ''' 
				echo "This is the Test stage"
				sleep 2
				'''
			}
		}
		stage('Deploy'){
			agent : {label 'jenkinsNode1'}
			steps{
				
				sh ''' 
				echo "This is the Deploy stage"
				sleep 2
				'''
			}
		}
 }
}
