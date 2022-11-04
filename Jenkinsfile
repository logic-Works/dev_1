node('built-in') 
{
    stage('Continuous Download_L') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_L') 
	{
    sh label: '', script: 'mvn package'
	}
}
