# MULTI-CLOUD-ARCHITECTURE
#Company: CodTech IT Solutions
#Intern Name: KALAIYARASI S
#Intern ID: CT04DF2844
#Domain: Cloud Computing
#Duration: 4 Weeks
#Mentor: Neela Santosh

As part of my final task at CodTech IT Solutions, I was assigned to design and demonstrate a multi-cloud architecture that integrates services across two cloud providers — Amazon Web Services (AWS) and Google Cloud Platform (GCP). The goal of this task was to gain practical exposure to cross-cloud interoperability, redundancy, and resource distribution, which are core concepts in real-world enterprise cloud deployments.

Project Overview:
In this task, I implemented a simple yet functional multi-cloud application where the frontend was hosted on AWS S3 and the backend API was deployed using Google Cloud Functions. The communication between the two services was secured and validated, ensuring seamless user interaction.

Key Components and Configuration
AWS (Amazon Web Services) – Frontend Hosting:
Created an S3 bucket configured for static website hosting.
Deployed a basic index.html file with a simple form interface.
Used JavaScript (main.js) to send requests to the backend API (GCP).
Configured appropriate bucket policies for public read access and proper MIME types.

GCP (Google Cloud Platform) – Backend API (Cloud Function):
Created a Cloud Function in Node.js (or Python) to handle incoming POST requests.
The function processed data from the form (e.g., name, email, message).
Set CORS headers to allow requests from the AWS S3 domain.
Validated deployment by testing real-time API calls from the hosted frontend.

Architecture Diagram:
A simplified multi-cloud architecture diagram was created showing:
AWS S3 (Static Website) → sends API requests → GCP Cloud Function (Serverless Backend)
This visually represents service distribution and interaction between two cloud environments.

![Image](https://github.com/user-attachments/assets/1f8a7683-876e-46ba-901c-89973c33bdb5)

Demonstration & Testing:
Deployed and tested the solution by accessing the AWS-hosted frontend and submitting form data.
Confirmed API communication by logging responses from GCP Cloud Functions.

Skills and Knowledge Gained
Multi-Cloud Design Principles:
Learned how to split services across AWS and GCP effectively
Understood the importance of redundancy, cost optimization, and platform strengths

Interoperability:
Implemented cross-cloud API communication using HTTP and CORS
Gained practical knowledge of handling networking and permission challenges

Cloud Deployment & Debugging:
Practiced deployment on both AWS and GCP
Learned to troubleshoot frontend/backend connectivity issues

#OUTPUT:

![Image](https://github.com/user-attachments/assets/5485d3b1-907d-4400-b96c-5ead3fa50572)
