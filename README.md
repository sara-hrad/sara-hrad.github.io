# Personal Website README

## Initial Setup

### Prerequisites
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) should be installed on your system.

### Getting Started
1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

## Running the Website Locally

To run the website locally for development and testing purposes, use the following command:

```bash
hexo server
```

This will start a local development server, and you can access your website by opening a web browser and navigating to `http://localhost:4000`. You can make changes to your website and see the live updates as you save your files.

## Deployment with GitHub Actions

This repository is set up to automatically deploy your website to GitHub Pages whenever you push new changes to the main branch. Here's how it works:

1. When you push new changes to the main branch, a GitHub Action workflow is triggered.

2. This workflow runs the necessary build and deployment steps to update your website.