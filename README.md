# React TypeScript E-Commerce App With GitHub Actions

A simple and responsive **E-Commerce Product List Application** built with **React, TypeScript, Redux Toolkit, RTK Query, Redux Persist, and Tailwind CSS**.

The project also includes an automated **CI/CD pipeline using GitHub Actions and a self-hosted runner** to build and validate the application whenever changes are pushed to the repository.

## 🚀 Project Overview

This project demonstrates a modern React application combined with a practical DevOps CI/CD workflow.

The application provides product browsing and shopping cart functionality, while GitHub Actions automates the application build process using a self-hosted runner.

## ✨ Application Features

* **Product Listing** – Fetches and displays products from a mock API.
* **Infinite Scrolling** – Dynamically loads additional products while scrolling.
* **Search Functionality** – Allows users to search for products.
* **Shopping Cart** – Add products and view total items and price.
* **Persistent Cart** – Cart data is preserved using Redux Persist and browser local storage.
* **Responsive Design** – Works across desktop, tablet, and mobile screen sizes.

## 🔄 CI/CD Pipeline

The project uses **GitHub Actions** to automate the application's build process.

A **self-hosted GitHub Actions runner** is used to execute the workflow instead of a GitHub-hosted runner.

### CI/CD Workflow

```text
Developer
    │
    │ Push Changes
    ▼
GitHub Repository
    │
    ▼
GitHub Actions
    │
    ▼
Self-Hosted Runner
    │
    ├── Checkout Source Code
    ├── Install Dependencies
    └── Build Application
    │
    ▼
Build Result
```

This provides hands-on experience with:

* Continuous Integration
* GitHub Actions
* Self-hosted runners
* Automated application builds
* Linux-based CI/CD environments
* Git-based development workflows

## 🏗️ Architecture

```text
                    GitHub Repository
                           │
                           ▼
                    GitHub Actions
                           │
                           ▼
                  Self-Hosted Runner
                           │
                           ▼
                  React Application
                           │
              ┌────────────┴────────────┐
              ▼                         ▼
         RTK Query                  Redux Toolkit
              │                         │
              ▼                         ▼
          Mock API                 Shopping Cart
                                        │
                                        ▼
                                 Redux Persist
                                        │
                                        ▼
                                  Local Storage
```

## 🛠️ Technologies Used

| Technology         | Purpose                       |
| ------------------ | ----------------------------- |
| React              | Frontend development          |
| TypeScript         | Type-safe development         |
| Redux Toolkit      | Global state management       |
| RTK Query          | API fetching and caching      |
| Redux Persist      | Persistent cart state         |
| Tailwind CSS       | Responsive styling            |
| Vite               | Development and build tooling |
| GitHub Actions     | CI/CD automation              |
| Self-Hosted Runner | CI/CD job execution           |

## 📁 Project Structure

```text
react-typescript-ecommerce-app/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── src/
│   ├── app/
│   │   └── store.ts
│   │
│   ├── components/
│   │   ├── CartSummary.tsx
│   │   └── ProductList.tsx
│   │
│   ├── features/
│   │   └── cart/
│   │       └── cartSlice.ts
│   │
│   ├── services/
│   │   └── productApi.ts
│   │
│   ├── types/
│   │   └── types.ts
│   │
│   ├── App.css
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## 🎯 DevOps Learning Objectives

This project provides practical experience with:

* Git and GitHub
* GitHub Actions
* CI/CD pipeline implementation
* Self-hosted GitHub Actions runners
* Automated React application builds
* Node.js application environments
* Repository-based automation

## 🚀 Future Improvements

The CI/CD pipeline can be extended with:

* Automated testing
* Docker containerization
* Docker Compose
* Docker image publishing
* AWS EC2 deployment
* Terraform infrastructure provisioning
* Ansible configuration management
* Nginx reverse proxy
* HTTPS/SSL
* Security scanning
* Production deployment automation

## 👨‍💻 Author

**Shyam Raut**

GitHub: `techconet57`


This project is created for **learning, practice, and DevOps portfolio purposes**.
