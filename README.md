# My-EKS-Terraform

for any error regard Helm run this command

helm repo add bitnami https://charts.bitnami.com/bitnami
If you're using AWS EFS CSI driver:
helm repo add aws-efs-csi-driver https://kubernetes-sigs.github.io/aws-efs-csi-driver/
If you're using AWS Load Balancer Controller:
helm repo add eks https://aws.github.io/eks-charts
helm repo update
You should see something like:

Successfully got an update from the "bitnami" chart repository
Run Terraform again
terraform apply
