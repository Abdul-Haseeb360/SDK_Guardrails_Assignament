# Guardrails Class 07

A Python project focused on implementing and exploring AI guardrails using the OpenAI Agents framework.

## 🚀 Quick Start

### Prerequisites
- Python 3.13 or higher
- [uv](https://docs.astral.sh/uv/) package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <https://github.com/Abdul-Haseeb360/SDK_Guardrails_Assignament>
   cd Guardrails_class_07
   ```

2. **Install dependencies**
   ```bash
   uv add openai-agents
   ```

## 📁 Project Structure

```
Guardrails_class_07/
├── main.py              # Main application entry point
├── pyproject.toml       # Project configuration and dependencies
├── README.md           # This file
└── .venv/              # Virtual environment (auto-created)
```

## 🛠️ Development Setup

### Virtual Environment Activation

**Using Git Bash:**
```bash
source .venv/Scripts/activate
```

**Using PowerShell:**
```powershell
.venv\Scripts\Activate.ps1
```

**Using Command Prompt:**
```cmd
.venv\Scripts\activate.bat
```

### Running the Application

```bash
# Using uv (recommended)
uv run chainlit run main.py

# Or activate venv first, then run
source .venv/Scripts/activate  # Git Bash
uv run python main.py
```

## 📚 Dependencies

- **openai-agents**: OpenAI's agent framework for building AI applications
- **chainlit**: Web interface for AI applications

## 🎯 Project Goals

This project is designed to explore and implement AI guardrails, focusing on:

- Safe AI interactions
- Content filtering and validation
- Ethical AI usage patterns
- Robust error handling

## 🔧 Configuration

The project uses `uv` for dependency management, which provides:
- Fast dependency resolution
- Reproducible builds
- Virtual environment management


## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## 📄 License

This project is part of the Guardrails Class 07 curriculum.

## 🆘 Troubleshooting

### Common Issues

**Virtual Environment Activation Issues:**
- If using Git Bash, use `source .venv/Scripts/activate`
- If using PowerShell, use `.venv\Scripts\Activate.ps1`

**Dependency Installation Issues:**
- Ensure you have Python 3.13+ installed
- Use `uv sync` to sync dependencies
- Check `pyproject.toml` for correct dependency versions

**Chainlit Issues:**
- Ensure all dependencies are installed: `uv add chainlit`
- Check if port 8000 is available
- Verify OpenAI API key configuration


---

**Note:** This project is part of an educational curriculum on AI guardrails and safe AI development practices.
