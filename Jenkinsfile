pipeline {
  agent any
  stages {
    stage('Cloning Git') {
      steps {
        git 'https://github.com/frannkyoa/img-docker-react.git'
      }
    }
    stage('Build Docker image') {
      steps{
         {
          sh "docker build . -t frannyoa/frankie_docker_1repo:REACT"
        }
      }
    }
 }
 }
