<div align="center">
  <h1>📚 Keploy Docs Website</h1>
  <img src="https://avatars.githubusercontent.com/u/92252339?s=200&v=4" height="150" alt="Keploy Logo"/>
  <p>Official documentation site for the <a href="https://keploy.io">Keploy</a> open-source platform</p>
</div>

---

> ⚠️ **Note:** Issue creation is disabled in this repository.  
> To submit a new issue, visit the [Keploy Dashboard Issue Tracker](https://github.com/keploy/dashboard/issues) or the [Main Repository](https://github.com/keploy/keploy/issues).

<p align="center">
  <a href="https://github.com/keploy/docs"><img src="https://img.shields.io/github/contributors/keploy/docs.svg" alt="GitHub contributors"/></a>
  <a href="https://github.com/keploy/docs"><img src="https://img.shields.io/github/issues/keploy/docs" alt="GitHub issues"/></a>
  <a href="https://join.slack.com/t/keploy/shared_invite/zt-357qqm9b5-PbZRVu3Yt2rJIa6ofrwWNg"><img src="https://img.shields.io/badge/Slack-@keploy-blue?logo=slack" alt="Slack"/></a>
  <a href="https://twitter.com/Keployio"><img src="https://img.shields.io/twitter/follow/keploy.svg?label=Follow&style=social" alt="Twitter Follow"/></a>
  <a href="https://github.com/keploy/docs"><img src="https://img.shields.io/github/license/keploy/docs.svg" alt="License"/></a>
</p>

## 🚀 Overview

[Keploy](https://keploy.io) is a no-code API testing platform that auto-generates tests from real user traffic.

This repository hosts the source for the official [Keploy Docs website](https://docs.keploy.io), built using Docusaurus 2.  
We are actively improving and evolving the documentation experience.

## 🛠️ Tech Stack

- **[Node.js](https://nodejs.org/)**  
- **[Yarn](https://yarnpkg.com/)**  
- **[React](https://reactjs.org/)**  
- **[Docusaurus 2](https://docusaurus.io/)**  
- **[GitHub Actions](https://github.com/features/actions)**  

## 🧑‍💻 Local Development

To contribute, set up the documentation website locally:

### 🔧 Installation

```bash
git clone https://github.com/<GITHUB_USERNAME>/docs.git
cd docs
npm install
npm start
```

Now open your browser at: [http://localhost:3000](http://localhost:3000)

> 💡 Tip: The development server hot-reloads as you edit the files.

### ✅ Build the Site

```bash
npm run build
```

## 🧹 Code Formatting with Prettier

To format code consistently:

```bash
npx prettier --write '**/*.{js,md}'
```

## ✨ Linting Markdown with Vale

[**Vale**](https://vale.sh) ensures your documentation is grammatically correct and follows our writing style.

### 📥 Installation

#### macOS (with Homebrew):
```bash
brew install vale
```

#### Manual (macOS/Linux):
1. Download latest binary from [Releases](https://github.com/errata-ai/vale/releases)
2. Extract and move to `/usr/local/bin/`:
```bash
sudo mv vale /usr/local/bin/
sudo chmod +x /usr/local/bin/vale
```

#### Windows:
Follow the [installation guide](https://vale.sh/docs/installation/#windows).

### ⚙️ Configuration

Ensure your `.vale.ini` file contains:

```ini
StylesPath = vale_styles
MinAlertLevel = error
```

### 🧪 Run Lint

```bash
vale versioned_docs/version-2.0.0/**/*.md
```

Fix any style or grammar errors highlighted in the terminal.

---

## 🤝 Contributing

We welcome all contributions, big or small! Please read our [CONTRIBUTING.md](/CONTRIBUTING.md) and [STYLE.md](/STYLE.md) guidelines before submitting a pull request.

> When your PR is merged, a new build is automatically deployed to [https://docs.keploy.io](https://docs.keploy.io).

---

## 🌟 Community & Support

Need help or want to share feedback? Join the conversation!

[![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://join.slack.com/t/keploy/shared_invite/zt-357qqm9b5-PbZRVu3Yt2rJIa6ofrwWNg)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/keploy/)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UC6OTg7F4o0WkmNtSoob34lg)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Keployio)

---

## 💖 Let's Build Together

Whether you're just starting out or a seasoned developer, **your contributions make a difference**.  
Check out the [issue tracker](https://github.com/keploy/keploy/issues) and help us make Keploy Docs better for everyone!
