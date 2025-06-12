# 🛠️ Contributor Guide: Working on a Specific Branch

Hi there! 👋  
Thanks for your interest in contributing. To make changes based on a specific branch (not just `main`), please follow the steps below.

---

## 🚀 Step-by-Step Instructions

### 1. Fork the Repository

Go to the repository page and click the **"Fork"** button at the top-right corner.

### 2. Clone Your Fork

```bash
git clone https://github.com/MillenniumMec-24/Spark.git
cd REPO-NAME
````

### 3. Add the Original Repository as Upstream

```bash
git remote add upstream https://github.com/MillenniumMec-24/Spark.git
git fetch upstream
```

### 4. Create a Branch from the Original Branch You Were Asked to Work On

For example, if you were asked to work on a branch called `feature-base`:

```bash
git checkout -b my-feature-branch upstream/feature-base
```

> Replace `my-feature-branch` with your own descriptive branch name.

### 5. Make Your Changes

Make your changes, add, commit, and push:

```bash
git add .
git commit -m "Your meaningful commit message"
git push origin my-feature
```

### 6. Open a Pull Request

* Go to your fork on GitHub.
* Click **"Compare & Pull Request"**.
* Make sure the base repository and branch are correct (e.g., `MillenniumMec-24/feature-base`).
* Add a title and description, then submit the pull request.

---

## 📝 Notes

* Don’t forget to **sync regularly** with the upstream branch to stay up to date:

```bash
git fetch upstream
git merge upstream/feature-base
```

* Feel free to ask if anything is unclear!


Thank you for contributing! 💜


