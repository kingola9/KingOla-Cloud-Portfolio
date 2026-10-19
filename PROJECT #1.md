#### *PROJECT 1*: *AZURE VIRTUAL MACHINE DEPLOYMENT & TROUBLESHOOTING*

#### **Project Overview 📌**

This project demonstrates hands-on experience deploying, configuring, and troubleshooting Linux virtual machines on Microsoft Azure.
It reflects real-world IT Support / Cloud Support responsibilities such as VM provisioning, authentication configuration, deployment issue resolution, and cost optimization using Azure CLI.

---

#### 🌍 Real-World Scenario

A support engineer may need to provision a Linux server, provide secure remote access, troubleshoot deployment or authentication issues, and manage the VM lifecycle while controlling cloud costs.

This project simulates that workflow by deploying an Ubuntu Linux VM in Azure, validating access, troubleshooting configuration and authentication issues, and managing the VM through its runtime lifecycle.

#### 🧑‍💻 Career Focus: IT Support / Cloud Support

#### ☁️  Environment & Tools: 

💡**Cloud Platform: Microsoft Azure**

💡**Operating System: Ubuntu 22.04 LTS**

💡**Deployment Methods: Azure Portal, ARM Templates**

💡**Command Line: Azure CLI**

💡**Authentication: SSH Keys, Username & Password**

---

#### 🎯 Key Objectives

- Deploy an Ubuntu 22.04 LTS virtual machine in Azure
- Configure and validate secure remote access
- Troubleshoot VM deployment and authentication issues
- Use Azure CLI to monitor and manage VM lifecycle states
- Apply cost-conscious cloud resource management practices

## 🔧 Hands-on Tasks Performed (What I Did)

1️⃣ **Virtual Machine Deployment**

Deployed Linux (Ubuntu 22.04 LTS) Virtual Machines using:
* Azure Portal (GUI)
* ARM Templates (Infrastructure as Code)
* Selected VM sizes, regions, networking, and storage configurations.


2️⃣ **Authentication Configuration**

Configured VM access using:
* SSH public/private key authentication
* Username and password login
* Validated secure remote access to Linux VMs.

3️⃣ **Troubleshooting & Issue Resolution:**

Resolved common Azure VM deployment and access issues, including:

❌ Managed OS disk reference errors

❌ OSProfile misconfiguration issues

❌ Authentication errors:

* Permission denied (publickey)

* Password authentication failures

* Verified Azure resource provider settings and template dependencies.

#### 🔎 Troubleshooting Approach

For each issue, I followed a structured troubleshooting process:

**Identify → Investigate → Correct → Validate**

- Identified the deployment or authentication failure
- Reviewed the relevant VM configuration, OS profile, disk references, or authentication settings
- Corrected the configuration or deployment issue
- Retested the VM to confirm successful deployment or access

  
4️⃣ **VM Monitoring & Lifecycle Management**

Used Azure CLI to monitor and manage VM runtime states:

- Running
- Stopped
- Deallocated

I started and stopped the VM during testing and deallocated it when it was no longer required.

👉 **Why this matters:**

Managing VM lifecycle states helps control unnecessary compute costs while maintaining the ability to restart resources when required.

#### 📸 Project Evidence

The screenshots below provide evidence of the VM deployment, configuration, remote access, resource management, monitoring, and cost-conscious lifecycle management performed during the project.


![531667842-9da55384-6751-45ec-b0ad-4c1483e46979~2](https://github.com/user-attachments/assets/6514c76c-a8f2-4df0-831e-c9e57af46bb2)
*Creation of Linux VM in process while configuring the VM size, region, OS image, OS Disk, Networking and storage configurations before deployment*

![531667841-ac131fb6-65c9-42bf-8c89-9839f0bcc888~2](https://github.com/user-attachments/assets/bbfa7fc4-1799-4b4f-b296-77252b8d8c89)
*Linux VM is in deployment in progress*

![531668820-fdff24b0-be1a-4e3e-a184-fe36f6ee096a~2](https://github.com/user-attachments/assets/8b6b9e78-a47a-43b2-ab8e-023ca373fe7a)
*Linux VM (Ubuntu 22.04 LTS) Successfully deployed*

![531667839-31f572c3-e69c-45a5-96e8-7b78b91a37bc~2](https://github.com/user-attachments/assets/91d721ca-44e2-426d-b773-2e00fd9e782a)
*Linux VM overview (running) after deployment*

![531667838-0e6ca802-29d9-44b7-aa40-6d93d8157ef5~2](https://github.com/user-attachments/assets/4cfb4d5e-6acd-429a-86ab-6619ae0ef4a4)
*Successfully connected to the (SSH) Azure CLI terminal (bash)*

![531668933-233aef51-ba94-4ea9-a4b3-65590b3c420b~2](https://github.com/user-attachments/assets/1b47cc13-0eef-4704-9eb7-e9977e134714)
*Resources in the Resource group (named: IntroAzureRG)*

![531669142-98da3ca0-ac9a-4ef4-97e9-2bdc68f142b8~2](https://github.com/user-attachments/assets/0e29a351-daca-4c3a-896f-7005a6b4dcb1)
*All resources in the Resource Manager*

![531669219-4d85cee0-4b4d-4348-b5b2-5cf67b683d9d~2](https://github.com/user-attachments/assets/813fd83f-f942-40c8-ab1e-1fee0dc2766b)
*Successfully Shutdown the VM and deallocated from the Azure CLI after checking the memory usage, running time, disk usage, creating of folder and creating of text file*

![531669484-c7a929ee-013b-4f04-996c-deaf6babda52~2](https://github.com/user-attachments/assets/ba9c1cd6-887d-4015-b27b-fb46ac3f0e92)
*Activity Log*

![531669519-fd8c926f-cb27-4124-a404-f8e67b67d934~2](https://github.com/user-attachments/assets/58035c18-df95-41ad-9c3f-8cec90d21158)
*Monitored VM runtime activity and deallocated the VM when it was no longer required to reduce unnecessary compute costs*

---

### 🧠 Key Takeaways

- Azure VM deployment requires careful configuration of compute, networking, storage, and authentication settings.
- Troubleshooting is more effective when problems are isolated and validated systematically.
- Azure CLI provides practical control over VM lifecycle operations.
- VM deallocation is an important cost-management practice when compute resources are no longer required.
- Infrastructure as Code with ARM templates improves repeatability and consistency.

---

### 🎯 Career Relevance: IT Support & Cloud Support

This project demonstrates practical experience supporting Azure Linux virtual machines, troubleshooting deployment and authentication issues, using Azure CLI, and managing VM lifecycle and cloud costs.

---

🛠 **Skills Demonstrated:**

- Microsoft Azure Virtual Machines
- Linux Administration (Ubuntu)
- Azure CLI Operations
- SSH & Remote Access
- ARM Template Troubleshooting
- Cloud Infrastructure Support
- Technical Troubleshooting
- VM Lifecycle Management
- Cloud Cost Awareness
- IT Support & Problem Solving

---

#### [ARM Template (JSON file)](https://github.com/kingola9/Azure-IT-Support-Portfolio/tree/8458c122e39d46c25c0636af285d20868e30bae5/PROJECT%20%231%20ARM%20Template)

#### ⭐ Final Recruiter Note

This project demonstrates my ability to deploy, access, troubleshoot, and manage Azure Linux virtual machines while applying structured problem-solving and cost-conscious cloud operations.
