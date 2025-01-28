# React App Deployment with GitHub Actions and GitHub Pages

This project demonstrates the use of **GitHub Actions** to automate the deployment of a React application to **GitHub Pages**. It includes a simple workflow to test and build the app and deploy it as a static site.

---

## Features

- **Automated Workflow**:

  - Triggered on commits to the `main` branch.
  - Installs Node.js and dependencies.
  - Tests a simple math `add` function.
  - Builds a React app with a counter that uses the `add` function.
  - Deploys the static site to the `gh-pages` branch for **GitHub Pages**.

- **React App**:
  - A basic counter app showcasing the tested `add` function.

---

## Workflow Details

The GitHub Actions workflow (`.github/workflows/deploy.yml`) includes the following steps:

1. **Trigger**: Activated on each commit to the `main` branch.
2. **Setup**: Installs Node.js and dependencies.
3. **Testing**: Runs a test script for the `add` function.
4. **Build**: Builds the React app into a static site.
5. **Deploy**: Publishes the built app to the `gh-pages` branch.

---

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed locally for development.
- **GitHub Pages**: Enable GitHub Pages for the repository (source: `gh-pages` branch).

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the app locally:

   ```bash
   npm run dev
   ```

4. Push changes to the `main` branch to trigger the workflow.

---

## Deployment

The React app is automatically deployed to GitHub Pages after every successful commit to the `main` branch.  
Visit the deployed app at: **https://aungmoe32.github.io/gh-action/**

---

## License

This project is open-source and available under the [MIT License](LICENSE).
