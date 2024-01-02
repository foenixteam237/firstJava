pipeline {
    agent any
    stages {
        stage('git repo & clean') {
            steps {
               //bat "rmdir  /s /q TicketBookingServiceJunitTesting"
                //bat "git clone https://github.com/kishancs2020/TicketBookingServiceJunitTesting.git"
              bat "git clone https://github.com/foenixteam237/fisrtJava.git"
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
