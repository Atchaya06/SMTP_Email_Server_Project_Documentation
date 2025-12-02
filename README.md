# SMTP_Email_Server_Project_Documentation
# SMTP Email Server Configuration using Postfix & Mailx

## 📌 Project Overview

This project demonstrates how to configure a basic SMTP mail server on a **CentOS Linux system** using **Postfix** and **Mailx**. The setup allows sending emails from the terminal using Gmail’s SMTP server with secure authentication.

---

## 🎯 Objective

To install, configure, and test a functional SMTP email server using Postfix and Mailx for sending mail from a Linux virtual machine.

---

## 🖥️ Environment

- **Operating System:** CentOS
- **Project Type:** Linux Server Configuration

---

## 🧰 Tools & Technologies

| Tool        | Purpose                        |
|-------------|--------------------------------|
| Postfix     | Mail Transfer Agent (MTA)      |
| Mailx       | Command-line mail utility      |
| bsd-mailx   | Mail utility package           |
| Nano        | File editing                   |
| chmod       | Permission management          |
| tail        | Monitor mail logs              |

---

## 🛠️ Installation Steps

### 1️⃣ Install Required Packages
```bash
yum install postfix
yum install mailx
yum install bsd-mailx
dnf config-manager --set-enabled crb
dnf install mailx
dnf install bsd-mailx
