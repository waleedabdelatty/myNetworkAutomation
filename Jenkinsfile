#!/usr/bin/groovy

// String branchName = env.BRANCH_NAME
// String gitCredentials = "CREDENTIAL_ID"
// String repoUrl = "https://github.com/waleedabdelatty/myNetworkAutomation.git"
  
pipeline {
  agent any
  
  environment { 
       // replace xyz with the copy pasted iD
       GitHubUser = credentials('b96a402b-87c5-4f8a-aab4-01b3e328da30')
  }
  
  stages {
        stage('clone repo') {
          steps {
            bash "git clone https://$GitHubUser_USR:$GitHubUser_PSW@github.com/waleedabdelatty/myNetworkAutomation.git"
          }
  }
               
    
