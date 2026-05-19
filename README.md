🚀 K8s Games
<div align="center">
🎮 Learn Kubernetes by Playing in 3D

Deploy Pods • Fix CrashLoopBackOff • Type Real kubectl Commands • Survive Production Incidents

<p align="center"> <img src="https://img.shields.io/badge/Kubernetes-3D%20Simulation-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" /> <img src="https://img.shields.io/badge/Three.js-WebGL-black?style=for-the-badge&logo=three.js" /> <img src="https://img.shields.io/badge/No%20Install-Play%20Instantly-success?style=for-the-badge" /> <img src="https://img.shields.io/badge/Open%20Source-Apache%202.0-orange?style=for-the-badge" /> </p>
🌐 Play Online
🎮 Main Game
👉 Play K8s Games
🧩 3D Architecture Designer
👉 Open K8s Draw
</div>
✨ What is K8s Games?

K8s Games is an interactive 3D Kubernetes simulator that runs directly in your browser.

Learn Kubernetes visually by:

🚀 Deploying applications
🛠 Fixing real production incidents
📦 Managing workloads
⚡ Scaling deployments
🔥 Handling outages
💻 Running real kubectl commands
🧠 Learning SRE troubleshooting workflows

No signup. No installation. No cluster required.

🖼 Preview
🎮 Kubernetes Game Simulation
5
🧩 K8s Draw — 3D Architecture Diagrams
6
⚡ Features
🎯 Learn by Doing
Real Kubernetes workflows
Real-world incidents
Real kubectl commands
Interactive troubleshooting
SRE-style debugging experience
🎮 Multiple Game Modes
Mode	Description
🚀 Campaign	20 levels across networking, storage, workloads & production K8s
🔥 Chaos Mode	Endless incidents until your cluster breaks
🏗 Sandbox	Freely design clusters and get architecture scores
⏱ Challenges	Timed outage & deployment scenarios
🧩 K8s Draw
A 3D Kubernetes Architecture Whiteboard

Think Excalidraw for Kubernetes, but fully interactive and 3D.

Features
🧱 Drag & drop K8s resources
🔗 Connect workloads visually
🏷 Rename and edit resources
🧠 Auto-layout by architecture tiers
📄 Export YAML
🖼 Export PNG diagrams
🔗 Share diagrams with URLs
⚡ Real Kubernetes API versions
☸️ Supported Kubernetes Resources

Supports 25+ Kubernetes resource types

Workloads
Pod
Deployment
ReplicaSet
StatefulSet
DaemonSet
Job
CronJob
Networking
Service
Ingress
NetworkPolicy
Storage
PVC
PV
StorageClass
Configuration
ConfigMap
Secret
Namespace
Scaling & Reliability
HPA
PodDisruptionBudget
ResourceQuota
RBAC
ServiceAccount
Role
ClusterRole
RoleBinding
ClusterRoleBinding
🚨 Real Incident Simulation

Practice troubleshooting production failures like a real SRE.

Included Incidents
🔥 CrashLoopBackOff
💥 OOMKilled
📦 ImagePullBackOff
🌐 DNS failures
💾 PVC Pending
⚠ Node NotReady
🔒 Certificate expiry
📈 HPA flapping
🚧 Rollout failures
🧠 API throttling

…and many more.

💻 Real kubectl Commands

Use actual Kubernetes commands directly inside the game.

get pods
describe deployment nginx
logs pod-1
scale deployment nginx --replicas=3
rollout status deployment nginx
drain node-1

✅ Includes:

Tab completion
Resource inspection
YAML viewer
Logs viewer
Scaling actions
🕹 Controls
Key / Action	Function
/	Open kubectl command bar
?	Help
Space	Pause / Resume
M	Metrics dashboard
Esc	Back to menu
1-9	Quick resource select
Left Click	Select resource
Left Drag	Move resource / rotate camera
Right Drag	Pan
Scroll	Zoom
🧠 Architecture Advisor

Your cluster gets scored across:

High Availability
Security
Scalability
Reliability
Cost Optimization
Production Readiness

Get instant feedback on your Kubernetes architecture.

🏆 Progression System
🎖 40 achievements
📈 30-level XP system
🧠 Learn from beginner → CKA-ready
⚙️ Tech Stack
Technology	Usage
Three.js r152	3D Rendering
Tailwind CSS	UI Styling
Vanilla ES6 Modules	Application Logic
WebGL	Browser Graphics
Highlights
⚡ No build step
📦 No dependencies
🚀 Runs entirely in browser
🧩 90+ files
💻 ~50K lines of code
🚀 Run Locally
git clone https://github.com/rohitg00/k8sgames.git

cd k8sgames

python3 -m http.server 8080

Open:

http://localhost:8080
📂 Project Structure
k8sgames/
├── game/
├── draw/
├── assets/
├── resources/
├── ui/
├── systems/
├── incidents/
├── kubectl/
└── index.html
🌟 Why K8s Games?

✅ Learn Kubernetes visually
✅ Practice SRE troubleshooting
✅ Understand resource relationships
✅ Improve kubectl skills
✅ Build production-ready thinking
✅ Design architectures in 3D

📜 License

Licensed under the Apache-2.0 License.
