#!/usr/bin/env groovy
pipeline {

    stages {
        stage("Prepare") {
            steps {
                bitbucketStatusNotify buildState: "INPROGRESS"
            }
        }
