# 👋 Pablo Sturm – DevOps Engineer in Progress

Hi! I'm Pablo, a multilingual IT professional with over 16 years of experience in systems administration, AV/IT, and infrastructure.  
I'm currently transitioning into a **DevOps/Site Reliability Engineer** role focused on:

🚀 Microsoft Azure (Virtual Machines, Storage, Networking)  
🔐 Entra ID & Microsoft Graph API  
⚙️ PowerShell scripting & automation  
🧱 Infrastructure as Code (Terraform)  
🔄 CI/CD with GitHub Actions and Azure DevOps  
📊 Monitoring with Grafana, Azure Monitor & App Insights

---

## 🛠️ Featured Repositories

| Repo | Description |
|------|-------------|
| [`entra-id-powershell`](https://github.com/psturm79/entra-id-powershell) | Automate Entra ID user and group management using PowerShell + Graph API |
| [`terraform-azure-lab`](https://github.com/psturm79/terraform-azure-lab) | Infrastructure as Code examples to deploy Azure resources |
| [`azure-automation`](https://github.com/psturm79/azure-automation) | Scripts to automate Azure resource creation and management |

---

📍 Based in the Netherlands 🇳🇱  
🗣️ Languages: Spanish (native), English (C1), Portuguese (C1), Dutch (B2)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/psturm79)

---

## 📂 Entra ID PowerShell Scripts

The scripts are located in the `scripts/` folder inside this repository:

- `Create-EntraUser.ps1`: Create a new Entra ID user.
- `Clone-EntraUser.ps1`: Clone attributes from an existing user to a new user.
- `Reset-Password.ps1`: Reset a user's password.
- `Manage-Groups.ps1`: Add or remove users from groups.

### 💡 Usage Examples

Run the scripts from the root folder like this:

```powershell
.\scripts\Create-EntraUser.ps1 -DisplayName "John Doe" -UserPrincipalName "john@domain.com" -Password "XxSecure123!"
