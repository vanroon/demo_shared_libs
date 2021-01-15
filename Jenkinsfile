@Library('devoteam-shared') _

import org.demo.Variables

pipeline {
    agent any
    stages {
        stage ('one'){
           steps {
              sayHello('caleb')
              script {
                echo Variables.greeting 
              }
           }
        }
    }
}
