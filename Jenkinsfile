node {
   echo 'pipleline start'
   
   stage('Checkout') {
        checkout scm
    }
    
    stage('Build') {
    }
    
    stage('Deploy') {
        echo 'Deploying....'
	sh 'cp index.html /var/www/html/index.html'
    }
}
