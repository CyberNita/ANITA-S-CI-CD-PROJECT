# ANITA-S-CI-CD-PROJECT
Build and deploy a web application using a CI/CD pipeline
# CI/CD Automated Web Deployment Project

## Live Demo
**Production URL:** https://anita-s-ci-cd-project-git-main-cybernitas-projects.vercel.app/

## Project Overview
This project demonstrates a fully automated **CI/CD (Continuous Integration / Continuous Deployment)** pipeline. It features a static website developed in HTML/CSS, integrated with a GitHub repository, and deployed to a serverless cloud environment.

## Tech Stack
* **Version Control:** GitHub
* **CI/CD Engine:** GitHub Actions
* **Environment:** Ubuntu-latest (Virtual Runner)
* **Cloud Hosting:** Vercel

## ⚙️ How the Pipeline Works
The deployment is managed by a custom YAML configuration (`.github/workflows/deploy.yml`). 
1.  **Trigger:** Every `push` to the `main` branch.
2.  **Environment Setup:** Provisions a fresh virtual machine.
3.  **Checkout:** Pulls the source code from the repository.
4.  **Deployment:** Synchronizes the code with the Vercel cloud environment.

## Proof of Deployment
see attached CI/CD Pipeline Success image
see attached Cloud Deployment Status image

**NOTE:**
Vercel was used for deployment instead of azure/ AWS because my azure free trial is expired and AWS keep rejecting my card. Thank you for your understanding.
