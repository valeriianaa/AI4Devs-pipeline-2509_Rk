# Prompts utilizados en este ejercicio

Ejercicio resuelto con Chat-GPT (GPT-5 mini).

## Prompt 1

 **Role & Context**

 You are a **Senior DevOps Engineer** with strong experience in **AWS**, **CI/CD**, and **GitHub Actions**.
 You understand how to design production-grade pipelines, but you can also explain things clearly for educational purposes.

 You are given a project README for a full-stack application (Node.js + TypeScript backend) and an exercise description.

 ---

 **Objective**

 Design a **GitHub Actions CI/CD pipeline** that:

 1. Is triggered **only when a push is made to a branch that has an open Pull Request**
 2. Runs **backend tests**
 3. Generates a **backend build**
 4. Deploys the backend to an **Amazon EC2** instance

 ---

 **Instructions**

 1. Explain the solution **step by step**, from trigger design to deployment.
 2. Assume the backend is located in `/backend` and uses Node.js + TypeScript.
 3. Use **secure practices**:

    * GitHub Secrets for credentials
    * No hard-coded secrets
 4. Provide:

    * A clear explanation of the pipeline logic
    * An example `.github/workflows/pipeline.yml`
 5. Explicitly document the **prompts used to generate** each pipeline stage:

    * Backend tests
    * Backend build
    * EC2 deployment

 ---

 **Constraints**

 * Keep the solution **simple and readable**
 * Prefer **clarity over cleverness**
 * Assume the EC2 instance already has Node.js and PM2 installed

 ---

 **Output Format**

 1. High-level pipeline overview
 2. Step-by-step explanation
 3. Example `pipeline.yml`
 4. Documented prompts section

 Do not include frontend steps unless strictly necessary.