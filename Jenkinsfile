pipeline {
    agent none
    stages {
        stage('Build') { 
            steps {
                sh '/opt/apache-maven-3.8.1/bin -B -DskipTests clean package' 
            }
        }
    }
}
