pipeline{
	agent { label 'jenkinsNode1'}
	stages{
		stage('Build'){
			steps{
				sh ''' 
					echo "This is a Build stage which is running in JenkinsNode1"
					sleep 2
				'''
			}
		}
		stage('Deploy'){
			steps{
				sh ''' 
				    echo "This is a Deploy stage which is running in JenkinsNode1"
					sleep 2
				'''
			}
		}
	}
}
