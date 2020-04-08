
pipelineDefault.run({
  // 测试
  stage('Test') {
    when(['dev'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：测试任务脚本（注意环境）"
      '''
    }
  }

  // 构建：开发环境
  stage('Build-dev') {
    when(['dev'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：构建任务脚本（注意环境）"
      '''
    }
  }

  // 部署：开发环境
  stage('Deploy-dev') {
    when(['dev'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：部署任务脚本（注意环境）"
      '''
    }
  }

  // 构建：预发环境
  stage('Build-release') {
    when(['release'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：构建任务脚本（注意环境）"
      '''
    }
  }

  // 部署：预发环境
  stage('Deploy-release') {
    when(['release'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：部署任务脚本（注意环境）"
      '''
    }
  }

  // 构建：生产环境
  stage('Build-prod') {
    when(['master'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：构建任务脚本（注意环境）"
      '''
    }
  }

  // 部署：生产环境
  stage('Deploy-prod') {
    when(['master'].contains(env.BRANCH_NAME)) {
      sh '''
        echo "在这里编写：部署任务脚本（注意环境）"
      '''
    }
  }
});