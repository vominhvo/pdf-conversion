﻿pipeline {
    agent any
    
    stages {
        stage('Pre') {
            steps {
                echo 'Hello world - Pre...' 
                sh 'docker --version'    
            }
        }
        
        stage('Build') {
            steps {
                echo 'Hello world - Building...' 
            }
        }
    }
}