# 👋 Pablo Sturm – DevOps Engineer in Progress
![PowerShell](https://img.shields.io/badge/PowerShell-4F5B93?style=flat&logo=powershell&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

Hi! I'm Pablo, a multilingual IT professional with over 16 years of experience in systems administration, AV/IT, and infrastructure.  
I'm currently transitioning into a **DevOps/Site Reliability Engineer** role with a focus on:

🚀 Microsoft Azure (VMs, Networking, Storage)  
🔐 Entra ID & Microsoft Graph API  
⚙️ PowerShell scripting & automation  
🧱 Infrastructure as Code with Terraform  
🔄 CI/CD using GitHub Actions & Azure DevOps  
📊 Monitoring with Grafana, Azure Monitor & App Insights

---

## 🛠️ Featured Repositories

| Repository | Description |
|------------|-------------|
| [`entra-id-powershell`](https://github.com/psturm79/entra-id-powershell) | Automate Entra ID user and group management using PowerShell and Microsoft Graph API |
| [`terraform-azure-lab`](https://github.com/psturm79/terraform-azure-lab) | Infrastructure as Code examples to deploy and manage Azure resources |
| [`azure-automation`](https://github.com/psturm79/azure-automation) | PowerShell scripts to automate Azure resource provisioning and configuration |

---

📍 Based in the Netherlands 🇳🇱  
🗣️ Languages: Spanish (native), English (C1), Portuguese (C1), Dutch (B2)  
🔗 [LinkedIn](https://www.linkedin.com/in/psturm79)

---

## 📂 Entra ID PowerShell Scripts

Find all scripts inside the `scripts/` directory:

- `Create-EntraUser.ps1` – Create a new Entra ID user.
- `Clone-EntraUser.ps1` – Clone an existing user's attributes to a new user.
- `Reset-Password.ps1` – Reset an Entra user's password.
- `Manage-Groups.ps1` – Add or remove users from Entra ID groups.

### 💡 Usage

You can run the scripts from the root folder:

```powershell
# Create new user
.\scripts\Create-EntraUser.ps1 -DisplayName "John Doe" -UserPrincipalName "john@domain.com" -Password "XxSecure123!"

# Clone user
.\scripts\Clone-EntraUser.ps1 -SourceUserPrincipalName "jane@domain.com" -NewUserPrincipalName "john@domain.com" -DisplayName "John Doe" -Password "XxSecure123!"

# Reset password
.\scripts\Reset-Password.ps1 -UserPrincipalName "john@domain.com" -NewPassword "NewP@ssword123"

# Add user to group
.\scripts\Manage-Groups.ps1 -Action Add -UserPrincipalName "john@domain.com" -GroupId "your-group-id"

