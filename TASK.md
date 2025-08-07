My Experience with Task 3: 
Infrastructure as Code (IaC) Using Terraform

In this task, I learned how to use Terraform to provision a local Docker container. The objective was to understand the basics of Infrastructure as Code (IaC) by automating container creation with Terraform.

I created a main.tf file that:

Pulled the nginx:latest Docker image

Started a container named nginx-container

Mapped container port 80 to a local port (initially 8080)

During the task, I ran important Terraform commands such as:

terraform init to initialize the project

terraform plan to see the actions before applying

terraform apply to create the container

terraform state list to view tracked resources

terraform destroy to remove the container

Challenges Faced:
Faced a port conflict error on port 8080, which I fixed by changing to another available port.

This task helped me understand the Terraform workflow and how it integrates with Docker to manage containerized environments declaratively.

