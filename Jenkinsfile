node{
    
    stage('checkout test script'){
        git branch: 'main', url: 'https://github.com/shubhamkushwah123/regression-test.git'
    }
    
    stage('execute regression test'){
        sh 'java -jar selenium-runnable.jar'
    }
    
    
}
