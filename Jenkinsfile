pipeline {
    agent amy
        stages {
            stage ("checkout from git") {
                steps {
                    git branch: 'main', url: 'https://github.com/bkrrajmali/newterraforminfra.git'
                }
            }
        }
}