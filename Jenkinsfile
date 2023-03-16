pipeline {
agent any 
tools {  
maven 'MAVEN_HOME'
}

stages {

stage ('compile')
{
steps {

sh "mvn compile"

}
}

stage ('test')
{
steps {

sh "mvn test"
}
}

stage ('package')
{
steps {

sh "mvn package"
}
}

stage ('install')
{
steps {

sh "mvn install"
}
}

}
}

