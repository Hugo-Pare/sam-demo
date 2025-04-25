# Solace Agent Mesh Tutorial
This tutorial will guide you through setting up and running Solace Agent Mesh, a powerful framework for building AI agent systems.
## 📚 Overview
Solace Agent Mesh is based on the official [Solace Agent Mesh](https://github.com/SolaceLabs/solace-agent-mesh) repository.
## 🚀 Quick Start (5 minutes)
Set up Solace Agent Mesh in just a few steps.
### ⚙️ System Requirements
To run Solace Agent Mesh locally, you'll need:
- **Python 3.10.16+**
- **pip** (comes with Python)
- **OS**: MacOS, Linux, or Windows (with WSL)
- **LLM API key** (any major provider or custom endpoint)
### 📋 Installation Steps
1. Clone the repository
   ```bash
   git clone https://github.com/Hugo-Pare/sam-demo.git
   cd sam-demo
   ```
2. Configure environment variables
   Open the .env file and modify these lines:
   ```env
   LLM_SERVICE_API_KEY=<LLM_SERVICE_API_KEY>
   LLM_SERVICE_ENDPOINT=<LLM_SERVICE_ENDPOINT>
   LLM_SERVICE_PLANNING_MODEL_NAME=<LLM_SERVICE_PLANNING_MODEL_NAME>
   ```
3. Create and activate a virtual environment
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
4. Install Solace Agent Mesh
   ```bash
   pip install solace-agent-mesh
   ```
5. Run the application
   ```bash
   solace-agent-mesh run
   ```
6. Access the web interface
   Open your browser and navigate to:

   http://localhost:5001

## 🤝 Support
For questions or issues, please refer to the [main repository](https://github.com/SolaceLabs/solace-agent-mesh) or open an issue in this demo repository.