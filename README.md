# 🔥 CloudOps Automation at Scale 🦅

> 🌟 You can use [Enterprise-grade CloudOps Automation Runbooks](https://cloudops.oceansoft.io), integrating AWS Cloud Foundations & FinOps best practices for DevOps and SRE teams 🌐

<details>
  <summary>🏆 The CloudOps Runbooks 👁️</summary>

  The CloudOps Runbooks project shows solid foundation but needs optimization in several key areas: dependency management, CI/CD pipeline efficiency, code organization following cloud-foundations patterns, and integration of battle-tested AWS automation tools.

  * **🏆 Mission**: Our mission is to simplify CloudOps Automation for DevOps and SRE teams by providing an extensive, community-driven repository of actions and runbooks that streamline day-to-day operations.
  * **👁️ Vision**: Our vision is to be the 🥇 One-Stop Multi-Cloud Platform Engineering & Best Practices Solution for all CloudOps Automation needs, allowing DevOps and SRE teams to automate their workflows with ease, improve efficiency, and minimize toil.

  <div align="left">
    <a href="https://www.linkedin.com/in/nnthanh" target="blank"><img align="center" src="https://img.shields.io/badge/-nnthanh-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nnthanh/" alt="Nhat-Thanh Nguyen" height="25" width="100" /></a>
    <a href="https://github.com/nnthanh101/" target="blank"><img align="center" src="https://img.shields.io/github/followers/nnthanh101?label=Follow&style=social&link=https://github.com/nnthanh101/" alt="Thanh Nguyen" height="25" width="100" /></a>
    <a href="https://www.facebook.com/groups/platformengineering" target="blank"><img align="center" src="https://img.shields.io/badge/Facebook-blue?style=flat-square&logo=facebook&logoColor=white&link=[https://www.linkedin.com/in/nnthanh/](https://www.facebook.com/groups/platformengineering)" alt="Nhat-Thanh Nguyen" height="25" width="100" /></a>  
  </div>
  
</details>

[![PyPI Version](https://img.shields.io/pypi/v/runbooks)](https://pypi.org/project/runbooks/)
[![Docker Hub](https://img.shields.io/docker/v/nnthanh101/runbooks?label=Docker)](https://hub.docker.com/r/nnthanh101/runbooks)
[![CI/CD Status](https://github.com/nnthanh101/runbooks/workflows/python-test/badge.svg)](https://github.com/1xOps/CloudOps-Runbooks/actions)
[![Coverage](https://codecov.io/gh/1xOps/CloudOps-Runbooks/branch/main/graph/badge.svg)](https://codecov.io/gh/1xOps/CloudOps-Runbooks)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

---

## 🎯 Key Features

### Core Capabilities
- [ ] **🏗️ AWS Cloud Foundations Integration** - Battle-tested templates and automation from AWS best practices
- [ ] **📊 Cloud Foundations Assessment Tool (CFAT)** - Automated AWS account assessment and compliance checking
- [ ] **🔍 Comprehensive Inventory Scripts** - Full AWS resource discovery and management
- [ ] **🎛️ Control Tower Automation** - Streamlined AWS Control Tower deployment and management
- [ ] **🔐 Identity & Access Management** - AWS IAM and SSO/IDC automation
- [ ] **📝 Centralized Logging** - CloudTrail and Config aggregation patterns
- [ ] **🏷️ Tagging Governance** - Organizational tagging policies and enforcement

### Technical Excellence
- **⚡ Lightning-Fast Toolchain** - Powered by `uv` for dependency management, ruff, ty
- **🐳 Production-Ready PyPi and Containers** - Multi-arch Docker images with Wolfi base
- **🧪 Comprehensive Testing** - Automated testing with pytest and coverage reporting
- **📚 Rich Documentation** - MkDocs-powered documentation site
- **🤖 AI-Ready** - Integration points for OpenAI/Anthropic and local LLMs

---

## 🚀 Quick Start

### 1. Installation via pip (Recommended) or uv (Fastest)

```bash
pip install runbooks

uv pip install runbooks
```

### 2. Installation via Docker
```bash
docker run -it nnthanh101/runbooks:latest runbooks --help
```

### 3. Run in VSCode's DevContainer 🐳

1. Open the project in **VSCode**.  
2. Install the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.  
3. **Reopen in Container**:  
   **Command Palette `Ctrl+Shift+P` → Reopen in Container**.  

---

## Python Template

<details>
  <summary>🛠️ Features</summary>

  * 🥉 ✅**Lightning-Fast Toolchain**: Powered by 📦 `uv` - Next-generation Python dependency and build management, 💅 `ruff` - Linting and formatting at blazing speed, and 🧪 pytest - Robust testing framework with coverage reports.
  * 🥈 ✅**Effortless CI/CD Pipelines**: 🛠️ Taskfile Automation - Say goodbye to manual SDLC repetitive tasks, 🐳 Containerized Workflows – 🛡️ Security-first practices and Multi-stage Wolfi-based Docker builds for scalable production-ready environments, and ⚙️ Auto-publish to `PyPI` and GitHub Container Registry (`GHCR`) with GitHub Actions.
  * 🥇 ☑️**CloudOps Automation and FinOps Toolkit** – Pre-configured hybrid-cloud workflows and seamlessly integrations (jupyterlab, mkdocs, boto3, moto) for managing cloud infrastructure 🌐.  
  
    | **Feature**              | **Toolchain**                            | **Purpose**                                        |
    |--------------------------|-------------------------------------|----------------------------------------------------|
    | 🛠️ Configuration         | `pyproject.toml`                 | Centralized configuration for dependencies, testing, and linting.  |
    | 🧹 Task Automation       | [`Taskfile`](https://taskfile.dev/) | Automates repetitive tasks like linting, testing, and publishing.  |
    | 📦 Python Dependencies   | [`uv`](https://docs.astral.sh/uv/)  | Lightning-fast dependency resolution, caching, and builds. |
    | 💅 Linting & Formatting  | [`ruff`](https://docs.astral.sh/ruff/) | Enforces code quality standards, auto-formatting, and import sorting.  |
    | 🧪 Testing Framework     | [`pytest`](https://docs.pytest.org/)  | Comprehensive unit tests, integration tests with coverage reporting.    |
    | 🐳 Docker Integration    | Dockerfile + [`DevContainer`](https://containers.dev/)  | Optimized wolfi-based multi-stage builds for CI/CD and local development environments. |
    | 🦾 CI/CD Pipelines       | [`GitHub Actions`](https://github.com/features/actions) | Automated builds, tests, and deployments to PyPI and GHCR. |
    | 📝 Security Compliance   | [`chainguard/wolfi-base`](https://hub.docker.com/r/chainguard/wolfi-base) + SBOM + Attestations | Ensures compliance, vulnerability scanning, and security transparency. |
  
</details>

<details>
  <summary>Project Structure</summary>
  
  > 🛠 End-to-end Production-grade project structure for successful 💎 CloudOps Automation and Visual Analytics FinOps projects 🚀
  
  ```
  cloudops-automation/
  ├── .devcontainer/     ## Dev Container configurations
  │   └── Dockerfile     ## Container image build file
  ├── .github/           ## CI/CD workflows
  │   ├── workflows/     ## GitHub Actions workflows
  │   └── templates/     ## Workflow templates
  ├── .vscode/           ## IDE-specific configurations
  ├── config/            ## Configuration files (YAML, JSON)
  ├── data               🔍 Where all your raw and processed data files are stored.
  │   ├── external       <- Data from third-party sources.
  │   ├── interim        <- Intermediate data that has been transformed.
  │   ├── processed      <- The final, canonical data sets for modeling.
  │   └── raw            <- The original, unprocessed, immutable data dump.
  │
  ├── docs               📓 A default mkdocs project; see mkdocs.org for details
  │   ├── api/                 ## API documentation
  │   ├── architecture/        ## Architecture diagrams
  │   ├── tutorials/           ## Tutorials and guides
  │   ├── getting-started.md   ## Quickstart guide
  │   └── index.md             ## Overview documentation
  │
  ├── logs/                    ## Log files for debugging
  |
  ├── models             🧠 Store your trained and serialized models for easy access and versioning.
  │
  ├── notebooks          💻 Jupyter notebooks for experiments and visualization.
  │   ├── data_exploration.ipynb
  │   ├── data_preprocessing.ipynb
  │   ├── model_training.ipynb
  │   └── model_evaluation.ipynb
  │
  ├── pyproject.toml     <- Project configuration file with package metadata for 
  │                         runbooks and configuration for tools like black
  │
  ├── src/                            ## 🧩 Source code for use in this project.
  │   ├── runbooks/                   ## Main module for CloudOps Runbooks automation
  │   │   ├── __init__.py             ## Package initializer
  │   │   ├── calculator.py           ## [Python101] Calculator
  │   │   ├── config.py
  │   │   ├── exceptions.py
  │   │   ├── utils.py                ## Utility scripts (logging, configs)
  │   │   └── cleanup.py              ## Cleanup automation runbook
  │   ├── main.py     
  ├── test/                           ## Unit and integration tests
  │   ├── conftest.py
  │   ├── __init__.py
  │   ├── test_calculator.py          ## [Python101] Test cases for calculator
  │   ├── test_utils.py               ## Test cases for utils
  │   └── test_exceptions.py         
  ├── templates/                      ## Terraform and CloudFormation templates
  ├── tools/                          ## Developer tools and scripts
  ├── .dockerignore                   ## Docker ignore file
  ├── .env                            ## Environment variables
  ├── .gitignore                      ## Git ignore file
  ├── .python-version                 ## Python version management
  ├── .gitignore
  ├── mkdocs.yml                      # Documentation generator configuration
  ├── README.md          🤝 Explain your project and its structure for better collaboration.
  ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
  │
  ├── reports            📊 Generated analysis (reports, charts, and plots) as HTML, PDF, LaTeX.
  │   └── figures        <- Generated graphics and figures to be used in reporting
  │
  ├── requirements.txt   🛠 The requirements file for reproducing the analysis environment, for easy environment setup.
  └── Taskfile           <- Taskfile with convenience commands like `task data` or `task train`
  ```

</details>
