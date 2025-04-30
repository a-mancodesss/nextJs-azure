

# Azure CI/CD using github actions - NextJs 🚀

This is a **Next.js** application deployed on an Azure VM using GitHub Actions for CI/CD.

## Features
- Built with **Next.js** for a simple, lightweight single-page application. ✨
- Automated deployment pipeline via **GitHub Actions**:
  - Push changes to `main` → Automatically deploys to the Azure VM.
- Hosted on an **Azure Virtual Machine**.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the app locally:
   ```bash
   npm run dev
   ```

## Deployment
- The `deploy.sh` script handles pulling, building, and starting the app on the VM:
  ```bash
  git pull origin main
  npm install
  npm run build
  npm start
  ```

## Technologies Used
- **Next.js**
- **Node.js**
- **Azure VM**
- **GitHub Actions**
