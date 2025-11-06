// 假设这是您仓库中的 Jenkinsfile
pipeline {
    agent any
    
    stages {
        stage('Checkout Code') {
            steps {
                echo "代码已检出，正在进入工作空间..."
                // 再次列出文件，确认环境和脚本文件分离
                sh 'ls -F' 
            }
        }
        
        stage('Verification') {
            steps {
                echo "执行代码验证步骤..."
                sh 'echo "CI/CD 流程来自 Git 仓库中的 Jenkinsfile"'
            }
        }
    }
}