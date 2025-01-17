pipeline {
    agent any
    tools {
        maven 'Maven_3.9.9' // Name of the Maven installation in Global Tool Configuration
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
