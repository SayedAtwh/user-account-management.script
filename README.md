# 🧪 User Account Management Script

![License](https://img.shields.io/badge/license-MIT-green)
![Bash](https://img.shields.io/badge/language-Bash-blue)
![Status](https://img.shields.io/badge/status-active-success)

## 📌 Overview
Automates Linux user account creation using Bash + CSV.  
Ideal for system administrators, DevOps engineers, and educational labs.

## 🚀 Features
- **CSV-driven input**: Manage users via `employee.csv`
- **Secure password generation**: Random strong passwords with `openssl`
- **Root validation**: Ensures script runs with admin privileges
- **Automated account creation**: Adds users with metadata + home directories
- **Password enforcement**: Forces password change on first login
- **Audit logging**: Saves credentials to `out.text`
- **Interactive CSV builder**: Script for manual entry and confirmation

## 📂 File Structure
| File | Description |
|------|-------------|
| `employee.csv` | Input usernames + full names |
| `out.text` | Output with generated credentials |
| `create_csv.sh` | Interactive CSV builder |
| `create_users.sh` | Main automation script |
| `script/script-create-csv-file.png` | Screenshot of CSV creation |
| `script/user-account-csv-workflow.png` | Workflow diagram |
| `script/capstone-title-slide.png` | Project title slide |
| `script/bash-script-preview.png` | Script preview |

## 📋 Usage
### 1. Prepare the CSV file
```bash
bash create_csv.sh

2. Run the automation script
bash
sudo bash create_users.sh
3. Check output
Created users and their passwords will be logged in out.text.

🖼️ Workflow

🛠️ Requirements
Linux environment

Bash shell

openssl installed

📚 Educational Value
Perfect for:

Capstone presentations

System administration labs

DevOps onboarding demos

📊 Demo Example
Sample employee.csv:

Username	Full Name
aws	Amazon Web Services
K8s	Kubernetes
Output out.text:

Code
aws,randomPassword123
K8s,securePassXYZ
👨‍💻 Author
Sayed Atwh — Third-year Computer Science student at Beni-Suef University, aspiring Cloud & DevOps Engineer.

## 📬 Contact
- GitHub: https://github.com/SayedAtwh
- LinkedIn: https://www.linkedin.com/in/sayed-atwh-sayed
- Email: sayed.atwh.sayed@example.com
