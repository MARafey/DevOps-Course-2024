# Devops-Course-FALL-2024
This repository contains a detailed walkthrough of the concepts and technologies I learned during the DevOps Course FALL-2024, taught by @Saim Safdar.

## What I Have Learned
Throughout this course, I gained hands-on experience with various DevOps tools and practices, including:

* Version Control: GitHub
* Containerization: Docker, Podman
* Orchestration: Kubernetes, Istio
* Cloud Services: ECS/EKS
* Infrastructure as Code (IaC):
* Terraform
* Pulumi
* Policy as Code: Kyverno
* Serverless Frameworks: Knative
* Networking: Ingress


## Blog 1
**Docker vs. Virtual Machines (VMs): A Comparison**  

Docker and Virtual Machines (VMs) both create isolated environments for applications but differ in functionality and use cases.  

- **Performance**: Docker containers are lightweight and start in seconds by sharing the host system’s kernel. VMs, which boot entire operating systems, take minutes to start.  
- **Use Cases**: Docker is ideal for microservices and rapid deployment. VMs are better for complete isolation and running multiple OSs, especially for legacy applications.  
- **Popularity**: Docker is highly demanded in cloud computing and DevOps for its speed and consistency, while VMs remain essential in enterprise settings for secure, multi-OS environments.  
- **Simplicity**: Docker is simpler to use, offering pre-made images and easy replication. VMs require more setup and expertise to install full OSs.  
- **User Experience**: Docker ensures consistent environments across machines. VMs provide a traditional desktop-like experience but are slower.  
- **Resource Requirements**: Docker is resource-efficient, supporting many containers on one machine. VMs are resource-intensive, limiting the number of instances.  

**Conclusion**:  
Docker is suited for scenarios requiring rapid deployment, scalability, and resource efficiency, while VMs are better for projects needing full isolation and OS environments. The choice depends on project needs.

## Blog 2
**Pulumi vs. Terraform: A Quick Comparison**  

Both Pulumi and Terraform let you set up cloud resources (like servers and databases) using code instead of doing it manually.  

### **Key Differences**  
- **Language**:  
  - **Terraform**: Uses its own language (HCL).  
  - **Pulumi**: Lets you use Python, JavaScript, or other familiar languages.  

- **Ease of Testing**:  
  - **Pulumi**: Works with regular programming tests.  
  - **Terraform**: Needs special testing tools.  

- **Storage**:  
  - **Terraform**: Saves setup info on your computer (or files you configure).  
  - **Pulumi**: Stores it in the cloud.  

- **Secrets Management**: Pulumi handles passwords and sensitive info more easily.  

- **Reusing Code**:  
  - **Terraform**: Uses "modules."  
  - **Pulumi**: Reuses code like regular programming projects.  

### **When to Use Each**  
- **Terraform**:  
  - You don’t mind learning a new, simple language.  
  - You want lots of online examples and a big community.  

- **Pulumi**:  
  - You know Python, JavaScript, or similar languages.  
  - You prefer treating cloud setup like regular programming.  

### **Bottom Line**  
- **Terraform**: The well-established tool with lots of support.  
- **Pulumi**: The modern option that works like your usual programming.


## Blog 3
This blog explains how to use GitHub Actions to automate the process of testing and deploying a Flask application. GitHub Actions is a tool that helps developers set up automatic workflows for tasks like checking code for errors, running tests, and deploying the app to a server. 

Here’s a simple breakdown:

1. **Flask App Setup**: You first need a working Flask application with necessary files, such as `app.py` and `requirements.txt`, which lists the app's dependencies.

2. **GitHub Actions Workflow**: You create a YAML file (`main.yml`) in your repository to define the steps for automation. The main steps include:
   - **Triggering** the workflow when changes are made to the code.
   - **Setting up Python** for your application.
   - **Installing dependencies** (like Flask).
   - **Running tests** to make sure everything works correctly.
   - **Deploying** the app to a platform like AWS or Heroku after the tests pass.

3. **Benefits**: 
   - The process ensures your code is always tested and ready for deployment.
   - It speeds up development by automating tasks.
   - It helps prevent errors by catching problems early.

4. **Customization**: You can also add more features, like using Docker or deploying to other cloud services, to make the automation work for your specific needs.

The blog emphasizes how GitHub Actions makes the deployment process more efficient, helping developers focus on coding instead of manual tasks.

### Links
- [Medium](https://medium.com/@m.a.rafey1215/automating-deployments-with-github-actions-for-a-flask-app-5938caa39c86)
- [Github](https://github.com/MARafey/GitHub-Actions-with-Flask-App) 


## Contacts

## **🌐 Platforms**  

### **1. Medium**  
- **Explore my articles and insights:**  
  [Visit Medium Profile](https://medium.com/@m.a.rafey1215)

---

### **2. GitHub**  
- **Discover my projects, contributions, and open-source work:**  
  [Visit GitHub Profile](https://github.com/MARafey)

---

### **3. Linkedin**  
- **Get a glimpse of my accomplishment:**  
  [Visit Linkedin Profile](https://www.linkedin.com/in/muhammad-abdur-rafey-a15124248/)  

---

### **4. Personal Website**  
- **Learn more about me, my portfolio, and my journey:**  
  [Visit My Website](https://muhammad-abdur-rafey.webflow.io/)

---
