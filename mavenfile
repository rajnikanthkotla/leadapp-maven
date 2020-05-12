pipeline
{
agent any
stages {

stage ( -'clean'--)
{
steps{
tool name: 'maven3.2', type: 'maven'
sh "mvn clean"
}
}

stage ( --'build'--){
steps {
tool name "maven3.8" type:'maven'
sh mvn build
}
}
}


}





}
