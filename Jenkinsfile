pipeline
{
agent any
stages
{
stage('Build')
{
steps
{
cmd 'javac HelloWorld.java'
cmd 'java -version'
}
}
stage('Run')
{
steps
{
cmd 'Java HelloWorld'
}
}
}
}
