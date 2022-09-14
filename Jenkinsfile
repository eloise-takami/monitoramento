pipeline{
    agent any 
    tools{
        maven 'maven'
    }

    stages {
        stage('Build && SonarQube Analysis') {
            steps {
                sh 'mvn clean package'     
            }
        }

    stage('Sending Artifact to Nexus') {
            steps {
                sh """
                curl -v -u admin:12345 \
                --upload-file /var/jenkins_home/workspace/eloise/target/simple-app-1.0-SNAPSHOT.war \
                http://44.210.15.179:8081/repository/elo/simple-app-1.0-SNAPSHOT.war
                """
            }
        }

}