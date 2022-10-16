pipeline{
    agent any{
        steps{
            step{
                sh 'echo akhila na pellam'
            }
        }
        steps{
            step{
                git url: 'https://github.com/prashanth463/game-of-life.git',
                branch 'master'
            }
        }
        steps{
            step{
                sh 'mvn package'
            }
        }

    }
}
