# 📧 n8n Email Trigger Agent

This repository contains an **n8n workflow** that triggers on incoming emails and performs automated actions. It can be used for use cases like automated replies, task creation, notification routing, and more.

## 🔧 Features

- Email trigger using **IMAP/SMTP or Gmail**
- Process automation using n8n nodes
- Customizable logic
- Easy import into n8n

## 📂 Files

- `emailAgent.json`: The exported n8n workflow file

## 🚀 How to Use

1. Open your [n8n instance](https://n8n.io/)
2. Click on "Import Workflow" (top right corner)
3. Upload `emailAgent.json`
4. Configure your email credentials (IMAP, Gmail, etc.)
5. Activate the workflow

## 🛠 Requirements

- [n8n](https://docs.n8n.io/getting-started/installation/)
- Valid email credentials with access to IMAP or Gmail API

## 📌 Notes

- Ensure your email provider allows third-party access.
- For Gmail users, enable access via OAuth2 or App Passwords.

## 📜 License

MIT License
