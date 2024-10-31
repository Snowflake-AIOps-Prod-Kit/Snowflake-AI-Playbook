# Snowflake AI Playbook

## Welcome to Snowflake AI Playbook by Snowflake AIOps Prod Kit

Snowflake AI Playbook is an open-source guide and resource collection for data engineers and data scientists, empowering them to build production-ready AI applications on Snowflake. This playbook includes structured templates, best practices, and complete project guides crafted to support you in deploying robust, scalable AI solutions following best practices in MLOps and data engineering.

## Organization Purpose

The Snowflake AIOps Prod Kit organization provides a central resource for production-level AI and data operation tools specific to the Snowflake platform. Our mission is to equip data professionals with the resources they need to become effective AI engineers on Snowflake by delivering complete, production-focused kits and guides.

### Repository Purpose

This repository, Snowflake AI Playbook, serves as a hands-on, step-by-step playbook tailored to Snowflake’s AI and data capabilities, including:

- **End-to-end AI Project Templates**: Production-grade templates and examples for common AI use cases.
- **Best Practice Guides**: Documentation for implementing efficient, maintainable, and scalable AI workflows on Snowflake.
- **Monitoring & Observability Tools**: Built-in monitoring tools for tracking model performance and data quality.
- **Environment Setup**: Ready-to-use Snowflake environments optimized for AI operations, with integration support for the Titan framework.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Credits & Acknowledgements](#credits--acknowledgements)

---

## Getting Started
### Prerequisites

- **Snowflake Account**: A Snowflake account to execute AI and data workflows.
- **Python**: Python 3.9+ recommended.
- **Titan Environment**: Optional but recommended for optimal environment setup and scaling.

### Quickstart
To get started quickly, clone the repository and explore the AI Project Templates in the templates/ folder:

```
git clone https://github.com/SnowflakeAIOpsProdKit/SnowflakeAIPlaybook.git
cd SnowflakeAIPlaybook/templates
```

## Features

- **AI Template Projects**: Production-quality code and data engineering templates for Snowflake.
- **Guides for Best Practices**: Tutorials on MLOps, data pipeline architecture, and Snowflake’s native AI tools.
- **Built-in Monitoring**: Scripts and configurations for model and data monitoring in production.
- **Pre-configured Environment**: Titan-powered Snowflake environments for quick deployment and scaling.

## Installation

1. Clone the Repository
```
git clone https://github.com/SnowflakeAIOpsProdKit/SnowflakeAIPlaybook.git
cd SnowflakeAIPlaybook
```

2. Set up Python Environment

Install the required Python packages:
```
pip install -r requirements.txt
```

3. Set up Snowflake

Configure your Snowflake credentials in the .env file, as detailed in the docs/ENV_SETUP.md file.

## Usage

Refer to the docs/ folder for detailed usage instructions, including:

- **Running a Project Template**: Follow along with example use cases in templates/.
- **Monitoring and Logging**: Setup guides for real-time monitoring tools.
- **Deploying AI Models**: Step-by-step deployment for model inference within Snowflake.

---
## Contributing

We welcome contributions! To contribute, please:

1.	Fork the repository and create a new branch.
2.	Submit a Pull Request (PR) with your changes, following the guidelines in CONTRIBUTING.md.

# Contributors

This project was developed with contributions from:

- [Atadata Consulting](www.atadataco.com)
- [Outlier Consulting](www.weareoutlier.com)

---
## Special Thanks

Our thanks to Titan for supporting environment setup and scalability solutions on Snowflake.

## License

This repository is open-sourced under the MIT License. For more details, see the LICENSE file.

## Credits & Acknowledgements

Snowflake AI Playbook was created in collaboration with Atadata Consulting and Outlier Consulting. Titan is credited for providing a robust and secure infrastructure on Snowflake.
