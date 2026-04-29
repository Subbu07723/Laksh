
 Application
* Repo: https://github.com/Vennilavanguvi/Trend.git
* Runs on port **3000**
  
 Docker
* Build image:
docker build -t my-app .
Run container:
docker run -p 3000:3000  my-app

Terraform
terraform init
terraform apply

DockerHub
* Pushed image to DockerHub

Kubernetes
* Deployed using YAML files
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

 Jenkins
* Setup CI/CD pipeline
* Auto build and deploy using GitHub webhook

Monitoring
Setup monitoring to check application health
