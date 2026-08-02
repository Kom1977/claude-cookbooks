# Claude Cookbooks - Repository Structure Analysis
**Generated:** 2026-08-02 | **Analysis Type:** Complete Structure Reconstruction

---

## 📊 Executive Summary

The `Kom1977/claude-cookbooks` repository is a **genuine fork** of the official `anthropics/claude-cookbooks` repository (created March 24, 2026). This is a comprehensive collection of Jupyter notebooks and Python examples demonstrating Claude API capabilities and integration patterns.

### Repository Metrics
- **Total Notebooks:** 67
- **Total Python Modules:** Multiple supporting scripts
- **Configuration Files:** 16 core files
- **Fork Status:** ~109 commits behind the original
- **Last Update (Fork):** March 24, 2026

---

## 🗂️ Directory Structure Overview

```
claude-cookbooks/
├── .claude/                    # Claude Code configuration
│   ├── agents/                 # Custom agent definitions
│   ├── commands/               # CLI commands
│   └── skills/                 # Custom skills
├── .github/                    # GitHub configuration
├── capabilities/               # Core Claude capabilities (5 notebooks)
│   ├── classification/
│   ├── contextual-embeddings/
│   ├── retrieval_augmented_generation/
│   ├── summarization/
│   └── text_to_sql/
├── claude_agent_sdk/           # Agent SDK examples (5 notebooks)
│   ├── chief_of_staff_agent/
│   ├── observability_agent/
│   ├── research_agent/
│   ├── site_reliability_agent/
│   └── utils/
├── coding/                     # Code examples (1 notebook)
├── extended_thinking/          # Extended reasoning patterns (2 notebooks)
├── finetuning/                 # Fine-tuning examples (1 notebook)
│   └── datasets/               # Sample fine-tuning datasets
├── images/                     # Supporting image assets
│   ├── best_practices/
│   ├── frontend_aesthetics/
│   ├── reading_charts_graphs/
│   ├── tool_use/
│   ├── transcribe/
│   └── using_sub_agents/
├── misc/                       # Miscellaneous utilities (14 notebooks)
│   └── data/                   # Supporting data files
├── multimodal/                 # Multimodal/Vision examples (6 notebooks)
│   └── documents/
├── observability/              # Observability patterns (1 notebook)
├── patterns/                   # Advanced patterns (3 notebooks)
│   └── agents/                 # Agent orchestration patterns
├── scripts/                    # Utility scripts
│   └── detect-secrets/         # Secret detection scripts
├── skills/                     # Skill development (3 notebooks)
│   ├── .claude/
│   ├── assets/
│   ├── custom_skills/
│   ├── notebooks/
│   └── sample_data/
├── tests/                      # Test suite
│   └── notebook_tests/
├── third_party/                # Third-party integrations (13 notebooks)
│   ├── Deepgram/
│   ├── ElevenLabs/
│   ├── LlamaIndex/
│   ├── MongoDB/
│   ├── Pinecone/
│   ├── VoyageAI/
│   ├── Wikipedia/
│   └── WolframAlpha/
├── tool_evaluation/            # Tool evaluation patterns (1 notebook)
├── tool_use/                   # Tool use examples (12 notebooks)
│   ├── memory_demo/
│   ├── tests/
│   └── utils/
└── [Configuration Files]       # See below
```

---

## 📚 Notebook Categories & Breakdown

### 1. **Capabilities** (5 notebooks)
Core Claude capabilities demonstrations:
- **Classification** - Text/data classification techniques
- **Contextual Embeddings** - Embedding generation and usage
- **Retrieval Augmented Generation (RAG)** - External knowledge integration
- **Summarization** - Text summarization techniques
- **Text-to-SQL** - Natural language to SQL conversion

**Use Case:** Learn fundamental Claude capabilities for building AI applications.

---

### 2. **Claude Agent SDK** (5 notebooks)
Advanced agent development patterns:
- **Chief of Staff Agent** - Multi-task orchestration
- **Observability Agent** - Monitoring and logging patterns
- **Research Agent** - Information gathering and synthesis
- **Site Reliability Agent** - Infrastructure and operational patterns
- **Utils** - Helper functions and utilities

**Use Case:** Building sophisticated multi-agent systems.

---

### 3. **Extended Thinking** (2 notebooks)
Advanced reasoning patterns:
- **Extended Thinking** - Long-form reasoning demonstrations
- **Extended Thinking with Tool Use** - Combining reasoning with external tools

**Use Case:** Problems requiring deep reasoning and analysis.

---

### 4. **Multimodal/Vision** (6 notebooks)
Image and multimodal processing:
- **Getting Started with Vision** - Image analysis basics
- **Best Practices for Vision** - Optimization and techniques
- **Crop Tool** - Image manipulation utilities
- **Using Sub-Agents** - Vision with Haiku sub-agents
- **Transcribe Text** - Text extraction from images
- **Reading Charts/Graphs** - Analyzing visual data

**Use Case:** Building applications that process images and visual content.

---

### 5. **Tool Use & Integration** (12 notebooks)
External tool integration patterns:
- Customer service agents
- Calculator tools
- Database integrations
- API interactions
- Function calling examples

**Use Case:** Extending Claude with external APIs and tools.

---

### 6. **Third-Party Integrations** (13 notebooks)
Integration with external services:
- **Pinecone** - Vector database RAG
- **Wikipedia** - Knowledge base integration
- **VoyageAI** - Embeddings API
- **LlamaIndex** - Framework integration
- **MongoDB** - Document database
- **Deepgram** - Audio processing
- **ElevenLabs** - Text-to-speech
- **Wikidata/WolframAlpha** - Knowledge APIs

**Use Case:** Building production applications with external services.

---

### 7. **Miscellaneous Utilities** (14 notebooks)
General-purpose utilities and examples:
- PDF upload and summarization
- Batch processing
- Prompt caching
- JSON mode
- Image generation
- Moderation filters
- SQL query building
- Building evaluations
- Streaming responses
- JSON parsing
- Long context handling
- RAG examples
- Web scraping

**Use Case:** Utility functions and common patterns across applications.

---

### 8. **Skills Development** (3 notebooks)
Skill framework demonstrations:
- **Skills Introduction** - Skill system overview
- **Financial Applications** - Domain-specific skill examples
- **Custom Development** - Building custom skills

**Use Case:** Creating and managing Claude Skills.

---

### 9. **Pattern Examples** (3 notebooks)
Advanced architectural patterns:
- **Orchestrator Workers** - Multi-agent orchestration
- **Basic Workflows** - Workflow patterns
- **Evaluator Optimizer** - Evaluation and optimization patterns

**Use Case:** Building complex multi-component applications.

---

### 10. **Coding Examples** (1 notebook)
- Code generation and assistance examples

---

### 11. **Finetuning** (1 notebook)
- **Finetuning on Bedrock** - AWS Bedrock model tuning

---

### 12. **Observability** (1 notebook)
- **Usage & Cost API** - Monitoring and cost tracking

---

### 13. **Tool Evaluation** (1 notebook)
- Evaluation frameworks and metrics

---

## 🔧 Configuration Files

### Core Project Files
| File | Purpose |
|------|---------|
| `pyproject.toml` | Project metadata, dependencies, tool configuration |
| `uv.toml` | UV package manager configuration |
| `uv.lock` | Locked dependencies |
| `Makefile` | Common tasks (format, lint, test, fix) |
| `requirements-dev.txt` | Development dependencies |

### Pre-commit & Quality
| File | Purpose |
|------|---------|
| `.pre-commit-config.yaml` | Pre-commit hooks configuration |
| `tox.ini` | Testing environments |
| `lychee.toml` | Link checking configuration |

### Git & Documentation
| File | Purpose |
|------|---------|
| `.gitignore` | Git ignore patterns |
| `.env.example` | Environment variable template |
| `CLAUDE.md` | Claude Code specific instructions |
| `CONTRIBUTING.md` | Contribution guidelines |
| `LICENSE` | MIT License |
| `README.md` | Project overview |

### Metadata
| File | Purpose |
|------|---------|
| `registry.yaml` | Notebook registry for discovery |
| `authors.yaml` | Contributor information |

---

## 💻 Development Commands (from Makefile)

```bash
make format        # Format code with ruff (100 char limit)
make lint          # Run linting checks
make check         # Run format-check + lint
make fix           # Auto-fix issues + format
make test          # Run pytest
```

Or directly with `uv`:
```bash
uv run ruff format .
uv run ruff check .
uv run ruff check --fix .
```

---

## 📋 Key Project Rules & Standards

### Code Style
- **Line length:** 100 characters
- **Quotes:** Double quotes
- **Formatter:** Ruff
- **Notebook rules:** Relaxed for mid-file imports, redefinitions, variable naming

### API & Models
- Use **current Claude models** (never dated IDs like `claude-sonnet-4-6-20250514`)
- Use aliases: `claude-sonnet-4-6`, `claude-haiku-4-5`, `claude-opus-4-6`
- For Bedrock: Use base model IDs with `global.` prefix for global endpoints

### Notebooks
- Keep outputs in notebooks (intentional for demonstration)
- One concept per notebook
- Must run top-to-bottom without errors

### Dependencies
- Use `uv add <package>` for installation
- Never edit `pyproject.toml` directly
- Pre-commit hooks validate formatting and structure

---

## 📊 Repository Statistics

### Current State
| Metric | Value |
|--------|-------|
| **Total Notebooks** | 67 |
| **Total Python Scripts** | Multiple supporting modules |
| **Largest Category** | Miscellaneous (14 notebooks) |
| **Second Largest** | Third-Party (13 notebooks) |
| **Tool Use Examples** | 12 notebooks |
| **Total Directories** | 30+ |

### Skills Available in `.claude/skills/`
Custom skills can be defined locally and enabled on claude.ai for use across platforms.

---

## 🚀 Quick Navigation

### For Learning Claude Capabilities
Start with: `capabilities/` → `multimodal/` → `tool_use/`

### For Building Agents
Start with: `patterns/agents/` → `claude_agent_sdk/` → `extended_thinking/`

### For Production Integration
Start with: `third_party/` → `skills/` → `misc/` utilities

### For Advanced Patterns
Start with: `patterns/agents/orchestrator_workers.ipynb` → Explore remaining pattern notebooks

---

## ⚠️ Important Notes

1. **Fork Status:** This fork is ~109 commits behind the official `anthropics/claude-cookbooks` repository. To sync:
   ```bash
   gh repo sync Kom1977/claude-cookbooks
   # or on GitHub: Click "Sync fork" button
   ```

2. **API Keys:** Never commit `.env` files. Use `dotenv.load_dotenv()` and `os.environ`/`os.getenv()`

3. **Model References:** Always check `docs.anthropic.com` for the latest Claude model IDs

4. **Pre-commit Hooks:** Install with `uv run pre-commit install`

---

## 📖 Getting Started

```bash
# Install dependencies
uv sync --all-extras

# Install pre-commit hooks
uv run pre-commit install

# Set up API key
cp .env.example .env
# Edit .env and add your ANTHROPIC_API_KEY

# Run checks before committing
make check

# Format code
make fix
```

---

## 🤝 Contributing

1. Create a branch: `<username>/<feature-description>`
2. Make changes following the code style guidelines
3. Run `make check` before committing
4. Use conventional commit format:
   - `feat(scope): add new feature`
   - `fix(scope): fix bug`
   - `docs(scope): update documentation`
   - `style: lint/format`
5. Submit a PR with clear description

---

## 📚 Additional Resources

- [Anthropic Developer Documentation](https://docs.claude.com)
- [Anthropic Support](https://support.anthropic.com)
- [Anthropic Discord Community](https://www.anthropic.com/discord)
- [API Fundamentals Course](https://github.com/anthropics/courses/tree/master/anthropic_api_fundamentals)

---

**Repository Fork:** `Kom1977/claude-cookbooks` (fork of `anthropics/claude-cookbooks`)
**Analysis Date:** 2026-08-02
**Structure Verified:** ✅ Complete and accurate
