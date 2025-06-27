node {
    // some block
    stage('Build') {
    // some block
    git branch: 'main', url: 'https://github.com/KarimLabidProf/HelloWorldProject_Jenkins.git'
    
    }
    stage('Run'){
        bat '''
    cd HelloWorldProject_Jenkins 
    javac HelloWorld.java 
    java HelloWorld
    '''
        
    }
}
