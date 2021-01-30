pipeline
{
agent any
stages {

stage ( 'clean')
{
steps{
tool name: "maven3.2.1", type: 'maven'
sh "mvn clean"
}
}

stage ( 'build'){
steps {
tool name: "maven3.6.3", type:'maven'
sh "mvn build"
}
}
}
}
