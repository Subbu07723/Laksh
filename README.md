# Deployment

## Repo



## Docker

docker build -t trend-app .
docker run -p 3000:3000 trend-app

## Terraform

terraform init
terraform apply

## Kubernetes

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## Jenkins

CI/CD used
