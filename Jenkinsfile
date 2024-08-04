pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // 这里可以添加构建相关的命令，例如 Maven 构建
                sh 'vn clean package'
            }
        }
        stage('Test') {
            steps {
                // 这里可以添加测试相关的命令
                sh 'vn test'
            }
        }
        stage('Deploy') {
            steps {
                // 这里可以添加部署相关的命令
                sh 'kubectl apply -f deployment.yaml'
            }
        }
    }
}