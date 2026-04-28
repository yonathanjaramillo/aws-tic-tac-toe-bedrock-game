## 📸 Screenshots

<img width="1920" height="1080" alt="{11F58DA4-C226-4C26-BB69-695C581A25F8}" src="https://github.com/user-attachments/assets/ce79481d-a53c-42f9-bfe8-59026c2b416d" />



# 🎮 Tic Tac Toe Game (AWS + Bedrock + EC2)

This project demonstrates how to generate, deploy, and host a web application using AWS services.

## 🚀 Overview

- Generated a Tic Tac Toe game using Amazon Bedrock
- Deployed the application on an EC2 instance
- Configured NGINX to serve the HTML file
- Accessed and managed the instance using AWS Systems Manager (Session Manager)

## 🧰 Tech Stack

- AWS EC2 (Linux)
- Amazon Bedrock (AI code generation)
- AWS Systems Manager
- NGINX (web server)
- HTML, CSS, JavaScript

## 🌐 Live Demo

[http://YOUR_PUBLIC_IP/tictactoe.html](http://100.53.51.228/tictactoe.html)

## ⚙️ Key Steps

1. Generated HTML game using Bedrock
2. Connected to EC2 using Session Manager
3. Created and edited file:
   ```bash
   sudo nano /usr/share/nginx/html/tictactoe.html
