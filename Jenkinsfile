pipeline {
    agent any

    stages {
     stage("Git Checkout"){
            steps{
                git branch: 'main', changelog: false, poll: false, url: 'https://github.com/StarGirlOxRaz/jest.git'
}
     }
     stage("UNIT testing"){
            steps{
               sh 'mvn test'
     }
    }
}