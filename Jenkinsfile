pipeline
{
agent any

stages

{

stage('Build')
{
steps
{
bat 'javac Helloworld.java'
bat 'java -version'
}
}

stage('Run')
{
steps
{
bat 'java Helloworld'
}
} 
}
}
