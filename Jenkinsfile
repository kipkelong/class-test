
node {
    def app

    stage('Clone Repository')
    {
        checkout scm
    }

    stage('Show me the files') {

        sh "ls -l"	
       
    }

    stage('Apply changes to the enviroment'){
        sh "ls -l"
        sh "php -s localhost:5000"
    }
    
