pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''#!./bin/bash
pwd'''
      }
    }
    stage('Stage') {
      steps {
        sh '''#!./bin/bash
pwd'''
      }
    }
    stage('Deploy') {
      steps {
        input 'Your build was successful, Deploy to Prod?'
      }
    }
  }
}