pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/var/jenkins_home/Maven/apache-maven-3.9.6/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
