pipeline {
agent any




stages {



stage('build') {



     steps {
        bat 'docker build -t name .' 
        bat 'docker run -p 5000:5000 name'
            }
}



 }
}
