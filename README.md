# 🌐 Azure Static Website Hosting

A cloud project demonstrating how I deployed my personal portfolio website using **Microsoft Azure Blob Storage Static Website Hosting**.

---

## Project Overview

This project showcases the deployment of a responsive portfolio website to Azure Storage using the Static Website feature.

The deployment process involved:

- Creating an Azure Storage Account
- Configuring Azure Storage
- Enabling Static Website Hosting
- Uploading website files to the `$web` container
- Publishing the website using the Azure Static Website endpoint

---

## Live Demo

🔗 **Live Website**

https://portfolio20.z5.web.core.windows.net/

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Microsoft Azure
- Azure Blob Storage
- GitHub

---

# 📸 Project Preview

This is the final deployed portfolio website.

![Portfolio Website](screenshots/01-portfolio-preview.png)

---

# Deployment Process

## Step 1 — Create an Azure Storage Account

Created a Storage Account that will host the static website.

**Configuration**

- Resource Group: Raphael2000
- Storage Account: portfolio20
- Performance: Standard
- Redundancy: LRS
- Primary Service: Azure Blob Storage

![Create Storage Account](screenshots/02-create-storage-account.png)

---

## Step 2 — Deployment Completed

Azure successfully created the Storage Account and deployment resources.

This confirms that all resources were provisioned successfully.

![Deployment Successful](screenshots/03-deployment-success.png)

---

## Step 3 — Enable Static Website Hosting

Enabled Azure Static Website Hosting and configured:

- Index Document: `po.html`
- Error Document: Default

Azure automatically generated the public website endpoint.

![Enable Static Website](screenshots/04-enable-static-website.png)

---

## Step 4 — Upload Website Files

Uploaded all website assets to the **$web** container.

The uploaded files include:

- HTML pages
- Images
- AVIF assets
- Portfolio images

Azure serves these files directly from Blob Storage.

![Upload Files](screenshots/05-upload-files.png)

---

# Repository Structure

```
Azure-Portfolio/
│
├── index.html
├── style.css
├── script.js
├── images/
├── screenshots/
└── README.md
```

---

# Skills Demonstrated

- Azure Blob Storage
- Azure Storage Accounts
- Static Website Hosting
- Cloud Deployment
- HTML
- CSS
- JavaScript
- Git & GitHub

---

# Learning Outcomes

Through this project I learned how to:

- Create Azure cloud resources
- Configure Azure Storage Accounts
- Enable Static Website Hosting
- Deploy a static website to Azure
- Upload files to Blob Storage
- Publish websites without using a traditional web server

---

**Chijioge Chisom Raphael**

Frontend Developer | Cloud Engineer (Microsoft Azure)
