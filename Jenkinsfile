pipeline {
    agent any

    stages {
        stage ('clone') {
            steps {
                git 'https://github.com/jeevangs11222/maven-helloworld.git'
            }
        }
        
        stage ('Test') {
            steps {
                echo 'testing'
            }
        }
        
        stage ('Deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}
