pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
               bat "rmdir  /s /q firstJava"
                //bat "git clone https://github.com/kishancs2020/TicketBookingServiceJunitTesting.git"
              bat "git clone https://github.com/foenixteam237/firstJava.git"
            }
        }
        stage('Compilation') {
            steps {
              bat 'javac HelloWorld.java'
            }
        }
        stage('run') {
            steps {
                bat "java HelloWorld"
            }
        }
       
    }
}
