pipeline
{
agent any
stages {

stage ( 'clean')
{
steps{
tool name: "maven1", type: 'maven'
sh "mvn clean"
}
}

stage ( 'build'){
steps {
tool name: "maven1", type:'maven'
sh "mvn package"
}
}
}
}
