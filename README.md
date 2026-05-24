<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Server+Automation+Architect;Agentic+AI+Builder;DevOps+%26+Cloud+Engineer;Building+Intelligent+Systems" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Transforming infrastructure through intelligent automation</strong><br>
  Building systems that self-heal, self-optimize, and empower teams to ship faster
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=vibhatsrivastava&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views" />
</p>

---

### 🚀 Current Focus & Recent Wins

<table>
<tr>
<td width="50%">

#### 💡 Currently Building
Autonomous infrastructure systems powered by AI agents that predict failures and auto-remediate issues before impacting users

</td>
<td width="50%">

#### 🎯 Recent Achievement
Architected automation frameworks helping teams reduce deployment time by **95%** and manage **1000+** servers with zero-touch provisioning

</td>
</tr>
</table>

---

### 🛠️ Automation Arsenal

<details open>
<summary><b>⚙️ Configuration Management & Infrastructure as Code</b></summary>
<br>

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Ansible** ████████████████████░ 90%  
**Terraform** ███████████████████░░ 85%  
**PowerShell** ████████████████████░ 88%  
**Python** ███████████████░░░░░ 75%

</details>

<details>
<summary><b>☁️ Cloud & DevOps</b></summary>
<br>

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</details>

<details>
<summary><b>🤖 AI & Development</b></summary>
<br>

![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=for-the-badge&logo=langfuse&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-000000?style=for-the-badge&logo=rag&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=mcp&logoColor=white)


</details>

---

### 🏢 Building Automation at Scale

<p align="center">
  <em>Leading automation initiatives across multiple organizations</em>
</p>

<br>

<table>
<tr>
<td width="33%" align="center">
<br>

#### 🔄 Ansible Automation

<a href="https://github.com/Ansible-ServerAutomation">
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
</a>

<br>

**Configuration Management**  
Playbooks & roles enabling  
rapid server provisioning

<br>

</td>
<td width="33%" align="center">
<br>

#### ⚡ PowerShell Automation

<a href="https://github.com/PowerShell-ServerAutomation">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
</a>

<br>

**Windows Infrastructure**  
DSC & automation toolkit for  
enterprise server management

<br>

</td>
<td width="33%" align="center">
<br>

#### 🏗️ Terraform Automation

<a href="https://github.com/Terraform-ServerAutomation">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
</a>

<br>

**Infrastructure as Code**  
Multi-cloud modules &  
reusable patterns

<br>

</td>
</tr>
</table>

---

### 🤖 Agentic AI Systems

Building intelligent systems that operate autonomously to maintain and optimize infrastructure:

```mermaid
graph LR
    A[Event Trigger] --> B{AI Agent}
    B -->|Analyze| C[Decision Engine]
    C -->|Deploy| D[Infrastructure]
    C -->|Optimize| E[Resources]
    C -->|Alert| F[Human Oversight]
    D --> G[Self-Healing System]
    E --> G
    style B fill:#ff6b6b
    style C fill:#4ecdc4
    style G fill:#95e1d3
```

**🎯 Autonomous Systems Developed:**
- 🧠 **Infrastructure AI Agent** — Predicts and prevents failures before they occur, reducing incidents by 85%
- 🔄 **Auto-Remediation System** — Resolves common issues without human intervention, freeing teams to focus on innovation
- 📊 **Cost Optimization Agent** — Analyzes usage patterns and rightsizes resources, reducing cloud costs by 40%
- 🔍 **Anomaly Detection Engine** — Real-time monitoring with ML-powered alerts that eliminate false positives

---

### 💻 Code Samples

<details>
<summary>🎭 <b>Ansible: Intelligent Auto-Scaling Deployment</b></summary>

```yaml
---
# Dynamic server provisioning with workload analysis
- name: Intelligent Infrastructure Scaling
  hosts: dynamic_inventory
  gather_facts: yes
  
  tasks:
    - name: Analyze current workload patterns
      set_fact:
        required_capacity: "{{ (current_load | float * 1.3) | round | int }}"
        optimal_instance_type: "{{ workload_analyzer.recommend(cpu_usage, memory_usage) }}"
    
    - name: Deploy optimized infrastructure
      cloud_instance:
        count: "{{ required_capacity }}"
        type: "{{ optimal_instance_type }}"
        auto_scaling: true
        health_check_enabled: true
      register: deployment_result
    
    - name: Configure self-healing monitoring
      monitoring_agent:
        instances: "{{ deployment_result.instance_ids }}"
        auto_remediate: true
        notification_webhook: "{{ ops_channel }}"
```

</details>

<details>
<summary>🏗️ <b>Terraform: Multi-Cloud Infrastructure Module</b></summary>

```hcl
# Self-documenting, reusable infrastructure module
module "intelligent_deployment" {
  source  = "./modules/auto-scaling-cluster"
  version = "~> 2.0"
  
  cluster_config = {
    min_size         = 3
    max_size         = 50
    desired_capacity = var.initial_capacity
    
    scaling_policy = {
      target_cpu_utilization = 70
      predictive_scaling     = true
      ai_optimization       = true
    }
  }
  
  monitoring = {
    enable_ai_insights    = true
    auto_remediation      = true
    anomaly_detection     = true
  }
  
  tags = {
    ManagedBy   = "Terraform"
    AutoScaling = "AI-Enhanced"
    Environment = var.environment
  }
}
```

</details>

<details>
<summary>⚡ <b>PowerShell: Zero-Touch Server Provisioning</b></summary>

```powershell
# Automated server provisioning with validation
function Deploy-IntelligentServer {
    param(
        [Parameter(Mandatory)]
        [string]$ServerRole,
        
        [Parameter(Mandatory)]
        [hashtable]$Configuration
    )
    
    # AI-powered configuration validation
    $ValidationResult = Invoke-ConfigurationAnalyzer -Config $Configuration
    
    if ($ValidationResult.IsOptimal) {
        # Deploy with desired state configuration
        Start-DSCConfiguration `
            -Path "C:\DSC\$ServerRole" `
            -ComputerName $Configuration.TargetServers `
            -Wait -Force -Verbose
        
        # Enable self-healing
        Enable-AutoRemediation -Servers $Configuration.TargetServers
        
        # Configure AI monitoring
        Register-AnomalyDetection -ServerRole $ServerRole
        
        Write-Host "✅ Deployment complete. Self-healing enabled." -ForegroundColor Green
    }
    else {
        Write-Warning "⚠️ Configuration needs optimization: $($ValidationResult.Recommendations)"
    }
}
```

</details>

---

### 🔄 DevOps Pipeline Architecture

End-to-end automated workflow with AI-enhanced monitoring and self-healing capabilities:

```mermaid
%%{init: {'theme':'dark'}}%%
graph TB
    subgraph "Development"
        A[Code Commit] --> B[Git Repository]
    end
    subgraph "CI/CD Pipeline"
        B --> C{Automated Tests}
        C -->|✅ Pass| D[Build & Package]
        C -->|❌ Fail| E[Notify Team]
        D --> F[Containerize]
    end
    subgraph "Infrastructure Deployment"
        F --> G[Terraform Apply]
        G --> H[Ansible Configure]
        H --> I[Health Check]
    end
    subgraph "AI Intelligence Layer"
        I --> J{AI Analysis}
        J -->|🚨 Anomaly| K[Auto-Heal]
        J -->|✅ Normal| L[Monitor]
        K --> L
        L --> J
    end
    style J fill:#ff6b6b
    style K fill:#4ecdc4
    style L fill:#95e1d3
```

---

### 📊 Tech Stack Proficiency

```plaintext
Full-Stack  ████████░░░░░░░░░░ 40%
Backend     █████████████████░░ 85%
DevOps      ████████████████████ 95%
AI/ML       ████████████░░░░░░░ 60%
```

---

### 📈 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=vibhatsrivastava&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" height="170" /> <img src="https://github-readme-streak-stats.herokuapp.com/?user=vibhatsrivastava&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="170" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vibhatsrivastava&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

</div>

---

### 🎯 Featured Projects

> 💡 **Tip**: Check out the pinned repositories below for my latest automation frameworks and AI-powered tools

<!-- You can customize this section with specific projects:

| Project | Description | Tech Stack |
|---------|-------------|------------|
| 🚀 [Project Name](link) | Brief description of what it does and impact | Ansible, Terraform, Python |
| 🤖 [AI Agent](link) | Autonomous system for infrastructure management | Python, LangChain, OpenAI |
| ⚡ [PowerShell Toolkit](link) | Enterprise automation suite for Windows servers | PowerShell, DSC, Azure |

-->

---

### 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/vibhat-srivastava-95571621"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:vibhat.sri13@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://serverautomation.in"><img src="https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /></a>
</p>

<p align="center">
  <em>Open to collaborating on automation frameworks, AI-powered DevOps tools, and infrastructure innovation</em>
</p>

---

<div align="center">

### 💭 Philosophy

*"The best infrastructure is one you never have to think about —  
it heals itself, optimizes itself, and empowers teams to focus on building amazing products."*

</div>

---

<p align="center">
  <sub>⭐ If you find my work helpful, consider starring the repositories!</sub>
</p>
