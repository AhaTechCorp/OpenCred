# SkillCertify / 技能认证

Welcome to SkillCertify, an open-source certification system designed to validate and certify skills across various domains. This project serves as a robust platform for managing and verifying certifications, ensuring that individuals possess the skills they claim to have in fields such as programming, electronics, mechanics, mathematical modeling, art, and maker activities.

欢迎来到SkillCertify，一个开源的跨领域技能验证和认证系统。该项目作为一个强大的平台，用于管理和验证认证，确保个人在编程、电子、机械、科学建模、美术和创客等领域拥有其声称的技能。

## Features / 功能特性

- **Multi-Domain Certification**: Support for a range of skills including, but not limited to, programming (C), electronics (E), mechanics (M), science (S), art (A), and maker (K).
- **Level-Based Proficiency**: Each skill is assessed and certified at different levels of proficiency, ensuring a detailed and granular evaluation.
- **Dynamic Query System**: Users can query certification statuses, verify the authenticity of certificates, and obtain detailed information about certified individuals.
- **Visual Badge System**: Incorporates a visual representation of skill proficiency through digital badges that are easy to share and recognize.
- **Open-Source Collaboration**: Allows the community to contribute to the continuous improvement of the certification criteria and processes.

- **多领域认证**：支持包括但不限于编程（C）、电子（E）、机械（M）、科学（S）、美术（A）和创客（K）等一系列技能。
- **基于等级的熟练程度**：每个技能都在不同的熟练程度上进行评估和认证，确保详细和细致的评价。
- **动态查询系统**：用户可以查询认证状态，验证证书的真实性，获取认证个人的详细信息。
- **视觉徽章系统**：通过容易分享和识别的数字徽章，将技能熟练程度的视觉表现形式纳入系统。
- **开源合作**：允许社区参与到认证标准和流程的持续改进中。

## Getting Started / 开始使用

To get started with SkillCertify, clone this repository to your local machine:

为了开始使用SkillCertify，克隆此仓库到您的本地机器：

```bash
git clone https://github.com/[your-github-username]/SkillCertify.git
```

### Prerequisites / 先决条件

- Python 3.8 or higher
- MySQL or any other relational database for storing certification data

- Python 3.8或更高版本
- MySQL或任何其他关系数据库用于存储认证数据

### Installation / 安装

Install the required dependencies by navigating to the project directory and running:

通过导航到项目目录并运行以下命令来安装所需的依赖：

```bash
pip install -r requirements.txt
```

## Usage / 使用方法

To start using the SkillCertify system, follow these steps:

要开始使用SkillCertify系统，请按照以下步骤操作：

1. **Initialize the Database**: Run the database schema found in `schema.sql` to set up your database.
2. **Configure Your Environment**: Set up your environment variables as described in `config/example.env`.
3. **Launch the Application**: Execute the main script to start the application:

1. **初始化数据库**：运行`schema.sql`中的数据库模式来设置您的数据库。
2. **配置您的环境**：根据`config/example.env`中的描述设置您的环境变量。
3. **启动应用程序**：执行主脚本以启动应用程序：

```bash
python main.py
```

## Contributing / 贡献

Contributions to SkillCertify are welcome! Please refer to `

CONTRIBUTING.md` for guidelines on how to make contributions.

欢迎为SkillCertify做出贡献！请参考`CONTRIBUTING.md`了解如何贡献的指南。

## License / 许可证

SkillCertify is released under the MIT License. See the `LICENSE` file for more details.

SkillCertify根据MIT许可证发布。更多详情请查看`LICENSE`文件。

## Acknowledgements / 致谢

Thanks to all contributors and users of the SkillCertify system. Your feedback and contributions help us make certification more accessible and reliable.

感谢所有SkillCertify系统的贡献者和用户。您的反馈和贡献帮助我们使认证变得更加容易和可靠。
