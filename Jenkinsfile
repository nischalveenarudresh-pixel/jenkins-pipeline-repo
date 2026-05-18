pipeline{
	agent {label 'jenkinsNode1'}
	stages{
		stage('Build'){
			sh ''' 
				echo "This is a build stage which is running in JenkinsNode1"
				sleep 2
			'''
		}
		stage('Deploy'){
			sh '''  
			    echo "This is a Deploy stage which is running in JenkinsNode1"
				sleep 2
			'''
		}
		stage('Test')
		{
			sh ''' 
			    echo "This is a Test stage which is running in JenkinsNode1"
				sleep2
			'''
		}
	}
}
