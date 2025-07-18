# 👋 Pablo Sturm – DevOps Engineer in Progress

![PowerShell](https://img.shields.io/badge/PowerShell-4F5B93?style=flat&logo=powershell&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

---

## About Me

Hi! I'm Pablo Sturm, a multilingual IT professional with over **19 years** of experience in systems administration, AV/IT, and infrastructure.  
Currently, I am transitioning into a **DevOps/Site Reliability Engineer** role focused on cloud automation, infrastructure as code, and scripting.

---

## 🛠️ Skills & Technologies

- **Cloud Platforms:** Microsoft Azure (VMs, Storage, Networking)  
- **Identity & Access Management:** Microsoft Entra ID & Microsoft Graph API  
- **Scripting & Automation:** PowerShell, REST APIs  
- **Infrastructure as Code:** Terraform  
- **CI/CD:** GitHub Actions, Azure DevOps Pipelines  
- **Monitoring:** Grafana, Azure Monitor, Application Insights  
- **Languages:** Spanish (native), English (C1), Portuguese (C1), Dutch (B2)  

---

## 📂 Entra ID PowerShell Scripts

Find all scripts inside the `scripts/` directory:

- `Create-EntraUser.ps1` – Create a new Entra ID user.  
- `Clone-EntraUser.ps1` – Clone an existing user's attributes to a new user.  
- `Reset-Password.ps1` – Reset an Entra user's password.  
- `Manage-Groups.ps1` – Add or remove users from Entra ID groups.

### 💡 Usage Examples

Run the scripts from the root folder like this:

```powershell
# Create new user
.\scripts\Create-EntraUser.ps1 -DisplayName "John Doe" -UserPrincipalName "john@domain.com" -Password "XxSecure123!"

# Clone user
.\scripts\Clone-EntraUser.ps1 -SourceUserPrincipalName "jane@domain.com" -NewUserPrincipalName "john@domain.com" -DisplayName "John Doe" -Password "XxSecure123!"

# Reset password
.\scripts\Reset-Password.ps1 -UserPrincipalName "john@domain.com" -NewPassword "NewP@ssword123"

# Add user to group
.\scripts\Manage-Groups.ps1 -Action Add -UserPrincipalName "john@domain.com" -GroupId "your-group-id"
```
## 📂 Featured Repositories

| Repository                                                               | Description                                                       |
| ------------------------------------------------------------------------ | ----------------------------------------------------------------- |
| [`entra-id-powershell`](https://github.com/psturm79/entra-id-powershell) | PowerShell scripts to automate Entra ID user and group management |
| [`terraform-azure-lab`](https://github.com/psturm79/terraform-azure-lab) | Terraform examples for deploying Azure infrastructure             |
| [`azure-automation`](https://github.com/psturm79/azure-automation)       | PowerShell scripts for Azure resource automation                  |

📫 Contact Me
LinkedIn: https://www.linkedin.com/in/psturm79

Email: pcsturm79@gmail.com

💡 “Automation is the future of IT – I build it script by script.”
