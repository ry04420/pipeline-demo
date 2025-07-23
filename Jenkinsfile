@Library('shared-lib-demo') _

import org.mycompany.GreetUtils

pipeline {
    agent any
    stages {
        stage('Say Hello') {
            steps {
                sayHello('Rohit')
            }
        }
        stage('Fancy Greet') {
            steps {
                script {
                    GreetUtils.fancyGreet('Rohit')
                }
            }
        }
    }
}
