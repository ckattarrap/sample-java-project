node {
    
stage('SCM') {
    git 'https://github.com/ckattarrap/sample-java-project.git'
}
  
  stage('Build') {
    script: 'mvn clean install package'
}
  
}
