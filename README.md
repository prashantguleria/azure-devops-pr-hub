# Azure DevOps PR Hub

[![Logo](src/main/resources/META-INF/azure-devops.svg)](https://github.com/prashantguleria/azure-devops-pr-hub)

**Azure DevOps PR Hub** is a powerful IntelliJ IDEA plugin designed to streamline the management of pull requests across multiple Git repositories. It provides a centralized hub to view, create, and manage PRs with a modern and intuitive interface.

---

> [!NOTE]
> This repository is currently used primarily for **Issue Tracking** and **Feedback**. The source code is closed-source for the time being.

---

## Key Features

- **Multi-Repo Pull Request Management**: View and manage pull requests from multiple repositories in a single, unified tool window.
- **Bulk Actions**: Efficiently approve, reject, abandon, or complete multiple pull requests simultaneously.
- **Modern UI**: A sleek, user-friendly interface that integrates seamlessly with the IntelliJ platform.
- **Smart Filtering**: Filter PRs by state (Active, Completed, Abandoned), author, and reviewer status.
- **Integrated Diff Viewer**: Review changes directly within IntelliJ's powerful diff viewer.
- **Seamless Authentication**: Securely manage your Azure DevOps Personal Access Tokens (PATs) using IntelliJ's Password Safe.

## 🛠️ Installation

Currently, the plugin can be installed from a pre-built JAR/ZIP file:

1. Download the latest release from the [Releases](https://github.com/prashantguleria/azure-devops-pr-hub/releases) page.
2. In IntelliJ IDEA, go to `Settings` > `Plugins`.
3. Click the gear icon and select `Install Plugin from Disk...`.
4. Select the downloaded file and restart IntelliJ.

## 📖 Usage

### Initial Setup
1. Open the **Azure DevOps PR Hub** tool window (usually anchored on the right).
2. Click the **Settings (gear)** icon to configure your Personal Access Token (PAT).
3. Once authenticated, the plugin will automatically detect repositories and list active PRs.

### Creating a PR
1. Navigate to the **Details** tab or click the **Add (+)** icon.
2. Select your feature and target branches.
3. Add a title, description, and optional work item ID.
4. Click **Create PRs** to initiate the pull requests across selected repositories.

## 🐛 Feedback and Issue Tracking

We value your feedback! If you encounter any bugs or have feature requests, please use the [GitHub Issues](https://github.com/prashantguleria/azure-devops-pr-hub/issues) section of this repository.

When reporting an issue, please include:
- A clear and descriptive title.
- Steps to reproduce the issue.
- Your IntelliJ IDEA version and OS.
- Any relevant logs (if applicable).

## 📄 License

The source code for Azure DevOps PR Hub is currently **private/closed-source**. All rights reserved.

---
