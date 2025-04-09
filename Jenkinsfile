@Library('shared-lib') _  // Import shared library

pipeline {
    agent any

    stages {
        stage('Common Build') {
            steps {
                script {
                    commonBuild(deploy: true, env: 'staging')
                }
            }
        }
    }
}
