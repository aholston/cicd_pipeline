# **CI/CD Pipeline Demo with AWS**

## **Overview**
This project demonstrates the implementation of a fully automated CI/CD pipeline using **AWS services**, showcasing my cloud infrastructure and DevOps skills. The focus of this project is not on coding proficiency but rather on leveraging AWS to automate the deployment, hosting, and scaling of a simple web application.

The application itself is intentionally kept simple—a static webpage with minimal JavaScript—to emphasize the AWS tools and processes used to deploy and manage it.

---

## **Features**
- **AWS CodePipeline** for Continuous Integration and Continuous Deployment (CI/CD).
- **Amazon S3** for hosting the static web application.
- **AWS CloudFront** for global content delivery via a Content Delivery Network (CDN).
- **AWS CloudFormation** for Infrastructure as Code (IaC) to define and deploy AWS resources.
- **Amazon CloudWatch** for monitoring and logging.
- **GitHub Integration**: Automatically triggers deployments upon commits to the GitHub repository.

---

## **Purpose**
The primary goal of this project is to:
1. **Showcase AWS Expertise**:
   - Automating deployments with **AWS CodePipeline** and **CodeBuild**.
   - Hosting and delivering content securely and at scale with **S3** and **CloudFront**.
   - Monitoring application and pipeline activity with **CloudWatch**.

2. **Demonstrate CI/CD Practices**:
   - Building a pipeline that seamlessly integrates source control (GitHub), testing, and deployment.
   - Ensuring an efficient and repeatable process for deploying updates.

3. **Highlight DevOps Skills**:
   - Using Infrastructure as Code (IaC) with **CloudFormation** for repeatable and consistent environments.
   - Emphasizing security and scalability through proper AWS configurations.

---

## **Architecture**
The architecture of this project includes:
1. **GitHub Repository**: Source control for the static web application and pipeline definitions.
2. **AWS CodePipeline**: Orchestrates the CI/CD process.
3. **AWS CodeBuild**: Builds and packages the application.
4. **Amazon S3**: Hosts the static web application as a static site.
5. **AWS CloudFront**: Delivers the content globally with low latency.
6. **Amazon CloudWatch**: Tracks logs and metrics for both the pipeline and application.


![Architecture Diagram](link_to_architecture_diagram_placeholder)

---

## **Application Details**
- **Purpose**: The application is a simple "Hello, DevOps!" static webpage that demonstrates the CI/CD pipeline's functionality.
- **Features**:
  - Displays a basic "Hello, DevOps!" message.
  - A button triggers a greeting message using JavaScript.
- **Technology Stack**:
  - HTML, CSS, and JavaScript for the frontend.

The application's simplicity ensures the focus remains on the AWS services and pipeline processes, not the code.

---

## **Setup and Deployment**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/aws-cicd-demo.git
   cd aws-cicd-demo
