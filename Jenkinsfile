pipeline {
    agent {label 'agent1'}


    stages {
        stage('Build') {
            steps {
                // 这里可以添加构建相关的命令，例如 Maven 构建
                sh 'pwd && ls -lah'
                 sh 'gradle --version'
            }
        }
        stage('Test') {
            steps {
                // 这里可以添加测试相关的命令
                 sh 'gradle --version'
            }
        }
        stage('Deploy') {
            steps {
                // 这里可以添加部署相关的命令
                 sh 'gradle --version'
            }
        }
    }
}