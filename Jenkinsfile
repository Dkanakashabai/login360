pipeline {
      agent any
      environment {
          AWS_ACCOUNT_ID="298446713913"
          AWS_DEFAULT_REGION="ap-south-1"
          CLUSTER_NAME="login360"
          SERVICE_NAME="login360-service"
          TASK_DEFINITION_NAME="first-run-task-definition:2"
          DESIRED_COUNT="2"
          IMAGE_REPO_NAME="298446713913.dkr.ecr.ap-south-1.amazonaws.com/login360"
          IMAGE_TAG="${env.BUILD_ID}"
          REPOSITORY_URI ="${AWS_ACCOUNT_ID}.dkr.ecr.${AWS_DEFAULT_REGION}.amazonaws.com/${IMAGE_REPO_NAME}"
          registryCredential = "shabai"
}
}
