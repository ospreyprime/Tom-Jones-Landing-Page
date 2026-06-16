# Chicha Landing Page

This repository contains the source code and assets for the Chicha landing page website.

## Prerequisites

Before getting started, make sure you have:

* A GitHub account
* Git installed on your computer
* Access to this repository

To verify Git is installed, run:

```bash
git --version
```

---

## Cloning the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/ospreyprime/Tom-Jones-Landing-Page.git
```

Navigate into the project directory:

```bash
cd <repository-name>
```

---

## Creating a New Branch

Before making changes, create a branch for your work.

Pull the latest changes:

```bash
git pull origin main
```

Create a new branch:

```bash
git checkout -b feature/your-feature-name
```

Examples:

```bash
git checkout -b feature/update-homepage
git checkout -b feature/add-new-section
git checkout -b fix/contact-form
```

---

## Making Changes

Edit the files as needed.

Common files include:

* `index.html`
* `privacy.html`
* `contact.html`
* CSS files
* JavaScript files
* Images and assets

Preview your changes locally before committing.

---

## Checking Modified Files

View modified files:

```bash
git status
```

---

## Staging Changes

Stage all changes:

```bash
git add .
```

Or stage individual files:

```bash
git add index.html
```

---

## Committing Changes

Create a commit with a clear message:

```bash
git commit -m "Update homepage content"
```

Examples:

```bash
git commit -m "Add FAQ section"
git commit -m "Update privacy policy"
git commit -m "Fix mobile layout"
```

---

## Pushing Changes

Push your branch to GitHub:

```bash
git push origin feature/your-feature-name
```

---

## Creating a Pull Request

1. Open the repository on GitHub.
2. Select **Pull Requests**.
3. Click **New Pull Request**.
4. Choose your branch.
5. Add a title and description.
6. Request a review if applicable.
7. Submit the Pull Request.

Do not merge directly into `main` unless specifically authorized.

---

## Keeping Your Branch Up to Date

Switch to the main branch:

```bash
git checkout main
```

Pull the latest changes:

```bash
git pull origin main
```

Switch back to your branch:

```bash
git checkout feature/your-feature-name
```

Merge the latest main branch:

```bash
git merge main
```

---

## Helpful Commands

View repository status:

```bash
git status
```

View commit history:

```bash
git log --oneline
```

View current branch:

```bash
git branch
```

Switch branches:

```bash
git checkout branch-name
```

---

## Questions or Issues

If you encounter any issues with cloning, committing, or pushing changes, contact the project maintainer before making changes to the main branch.
