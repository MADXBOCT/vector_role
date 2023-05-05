pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/MADXBOCT/vector_role.git'
                sh "molecule test"
            }
            }
        }
}
