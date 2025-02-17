pipeline{
    tools{
        jdk 'JAVA _HOME'
        maven 'M2_HOME'
    }
    agent any
    
    stages{
        
        stage("checkout"){
            steps{
                git 'https://github.com/Parthamaharana/jenkins-1.git'
            }
        }
        stage("compile"){
            steps{
                sh 'mvn compile'
            }
        }
        stage("test"){
            steps {
                echo 'test sucesfully completed'
            }
        }
		stage("package") {
            steps {
                echo 'package sucesfully completed'
            }
        }
    }
}
