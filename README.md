<h1 align=center>Create NPM Package 🚀</h1>
<br>

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![CodeQL Security Analysis](https://github.com/ToolsHive/Create-Npm-Package/actions/workflows/codeql.yml/badge.svg)](https://github.com/ToolsHive/Create-Npm-Package/actions/workflows/codeql.yml)
[![Dependabot Updates](https://github.com/ToolsHive/Create-Npm-Package/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/ToolsHive/Create-Npm-Package/actions/workflows/dependabot/dependabot-updates)
![GitHub last commit](https://img.shields.io/github/last-commit/ToolsHive/Create-Npm-Package)
![Windows](https://img.shields.io/badge/platform-windows-blue)
![Linux](https://img.shields.io/badge/platform-linux-yellowgreen)
![macOS](https://img.shields.io/badge/platform-macOS-orange)
[![GitHub](https://img.shields.io/github/license/ToolsHive/Create-Npm-Package)](https://github.com/ToolsHive/Create-Npm-Package/blob/main/LICENSE)
![code-size](https://img.shields.io/github/languages/code-size/ToolsHive/Create-Npm-Package)
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

A CLI tool for creating starter templates for npm packages using TypeScript or JavaScript, tailored to simplify package development.

## 📚 Table of Contents

- [📚 Table of Contents](#-table-of-contents)
- [✨ Features](#-features)
- [💻 System Requirements](#-system-requirements)
- [📥 Installation](#-installation)
- [🛠️ Usage](#️-usage)
- [❓ FAQ](#-faq)
- [🐞 Troubleshooting](#-troubleshooting)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

## ✨ Features

- 🔥 Quickly scaffold a new npm package project.
- 🎯 Select between TypeScript or JavaScript for your starter template.
- 🛠️ Generates a pre-configured `package.json` with the selected template.
- 🧹 Sets up essential files for a clean and maintainable project structure.
- ✅ Includes basic configurations for linting and formatting.
- 🎉 Easy-to-use CLI for seamless setup and initialization.
- 📦 No need to install globally, just use with `npx`.

## 💻 System Requirements

- **Node.js**: >= 18.20.1
- **npm**: >= 9.2.0

⚠️ Ensure these are installed on your system before using this tool.

## 📥 Installation

You can install this package globally using npm to use the CLI tool directly in your terminal:

```bash
npm install -g @toolshive/create-npm-package
```

## 🛠️ Usage

To create a new npm package starter template, run the following command:

```bash
npx @toolshive/create-npm-package
```

This will prompt you to select whether you want to use TypeScript or JavaScript for your project.

## ❓ FAQ

**Q: Do I need to install this package globally?**

A: No, you can use it directly with `npx`, so there’s no need for a global installation.

**Q: Does this tool support both JavaScript and TypeScript?**

A: Yes, during setup, you can choose between TypeScript or JavaScript for your project.

## 🐞 Troubleshooting

- **🚫 Error: "Command not found"**  
  Ensure you have Node.js and npm installed. Run `node -v` and `npm -v` to check.

- **🔒 Permissions Error on Installation**  
  Use `sudo` for global installations:

  ```bash
  sudo npm install -g @toolshive/create-npm-package
  ```

- **💻 Installation Issues on Windows**
  Use PowerShell or Command Prompt with administrative rights.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
