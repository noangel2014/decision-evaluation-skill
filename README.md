# Decision Evaluation Skill

> **Evaluate important decisions through 7 professional analytical frameworks**

[![Skill Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/noangel2014/decision-evaluation-skill)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Claude%20Code%20%7C%20WorkBuddy%20%7C%20OpenClaw-orange.svg)](https://github.com/noangel2014/decision-evaluation-skill)

## 📖 Overview

The **Decision Evaluation Skill** is a comprehensive AI-powered tool that helps you make better decisions by analyzing them through seven distinct professional frameworks. Instead of relying on gut feeling or single-perspective analysis, this skill systematically evaluates your choices from multiple dimensions to reveal insights you might have missed.

## 🎯 What This Skill Does

- **Multi-Framework Analysis**: Examines decisions through 7 independent analytical lenses
- **Objective Scoring**: Each framework provides a 0-100 score for quantifiable comparison
- **Comprehensive Reports**: Generates detailed analysis with actionable insights
- **Framework Consensus**: Identifies agreement and disagreement across frameworks
- **Decision Support**: Helps you think clearly about complex choices

## 🚀 Quick Start

### Installation

1. **Clone or Download this Repository**
   ```bash
   # Clone the repository
   git clone https://github.com/yourusername/decision-evaluation-skill.git
   
   # Or download as ZIP and extract
   ```

2. **Place the Files in Claude Code's Skills Directory**
   - The `decision-evaluation` folder should be placed in:
     - **macOS/Linux**: `~/.claude/skills/`
     - **Windows**: `%USERPROFILE%\.claude\skills\`

3. **Restart Claude Code** if it's already running

### Alternative: Manual Installation

Simply clone this repository and copy the `decision-evaluation` folder to your Claude Code skills directory.

### Basic Usage

Simply describe your decision to the AI:

```
User: "I'm trying to decide whether to accept a job offer at a startup or stay at my current company."

AI: "I'll help you analyze this career decision through seven professional frameworks. Let me gather some information first..."
```

The AI will:
1. Guide you to provide relevant decision context
2. Analyze your decision through all 7 frameworks
3. Present a comprehensive analysis report
4. Highlight key insights and trade-offs

## 📊 The Seven Frameworks

### 1. Cost-Benefit Analysis
**Best for**: Financial decisions, resource allocation
- Quantifies all costs against all benefits
- Calculates ROI and net value
- Evaluates economic viability

### 2. SWOT Analysis
**Best for**: Career moves, competitive situations
- Examines Strengths, Weaknesses, Opportunities, Threats
- Strategic positioning assessment
- Internal and external factor analysis

### 3. Decision Matrix (Weighted Criteria)
**Best for**: Complex multi-factor decisions
- Multi-criteria weighted evaluation
- Objective scoring across prioritized factors
- Systematic comparison of options

### 4. ICE Framework
**Best for**: Resource-constrained choices, quick prioritization
- Impact, Confidence, Ease scoring
- Quick prioritization and opportunity assessment
- Simple but effective ranking

### 5. Risk-Reward Assessment
**Best for**: High-stakes decisions, investments
- Compares potential gains vs losses with probabilities
- Evaluates asymmetric risk/reward profiles
- Downside protection analysis

### 6. Eisenhower Matrix
**Best for**: Time-sensitive decisions, prioritization
- Importance and urgency prioritization
- Time management and action prioritization
- Helps distinguish urgent vs important

### 7. Regret Minimization Framework
**Best for**: Life-changing decisions, values-based choices
- Projects future regret at 1, 5, 10+ years
- Long-term perspective and values alignment
- Connects decisions to life goals

## 📋 Example Output

The skill generates a comprehensive report including:

```markdown
# Decision Analysis Report

## Summary Dashboard

| Framework | Score | Key Insight |
|-----------|-------|-------------|
| Cost-Benefit Analysis | 72/100 | Economic benefits significant, but high initial cost |
| SWOT Analysis | 68/100 | Strong advantages, but competitive threats exist |
| Decision Matrix | 82/100 | High weighted score, meets core criteria |
| ICE Framework | 70/100 | High impact but moderate implementation difficulty |
| Risk-Reward Assessment | 65/100 | Good returns with manageable risks |
| Eisenhower Matrix | 88/100 | Important and urgent, prioritize action |
| Regret Minimization | 91/100 | Low long-term regret probability |

## Framework Consensus

**Frameworks supporting this decision** (score ≥ 60):
- Eisenhower Matrix: 88/100
- Regret Minimization: 91/100
- Decision Matrix: 82/100

**Frameworks opposing this decision** (score < 40):
- None

## Key Insights
[Detailed analysis and recommendations...]
```

## 💡 Use Cases

### Career Decisions
- Job change opportunities
- Career path choices
- Skill development investments
- Relocation decisions

### Financial Decisions
- Investment opportunities
- Major purchases (house, car)
- Business investments
- Financial planning

### Life Planning
- Education choices
- Relationship decisions
- Lifestyle changes
- Personal projects

### Business Strategy
- Product launches
- Market expansion
- Partnership decisions
- Resource allocation

## 🎓 How It Works

### Step 1: Information Collection
The AI guides you to describe your decision with key details:
- Decision summary and background
- Options being considered
- Key considerations and constraints
- Goals and values

### Step 2: Multi-Framework Analysis
The AI analyzes your decision through each framework independently:
- Reads framework-specific methodology
- Applies analytical process
- Generates detailed analysis
- Assigns objective score (0-100)

### Step 3: Synthesis & Reporting
All analyses are combined into one comprehensive report:
- Individual framework reports
- Summary dashboard
- Consensus analysis
- Key insights and guidance

## 🔧 Technical Details

### File Structure
```
decision-evaluation/
├── SKILL.md                          # Main skill definition
├── README.md                         # This file
└── references/                       # Framework documentation
    ├── cost-benefit-analysis.md
    ├── swot-analysis.md
    ├── decision-matrix.md
    ├── ice-framework.md
    ├── risk-reward-assessment.md
    ├── eisenhower-matrix.md
    ├── regret-minimization.md
    └── decision-template.md          # Optional structured input template
```

### Platform Compatibility
- ✅ **Claude Code**: Full support (primary platform)
- ✅ **WorkBuddy**: Full support
- ✅ **OpenClaw**: Full support
- ✅ **Other AI Platforms**: Should work with any AI assistant that supports skills/plugins

### Requirements
- No external dependencies
- No API keys required
- No network requests
- Fully offline-capable

## 🛡️ Privacy & Security

- **No Data Storage**: Your decisions are analyzed in-session and not stored
- **No External APIs**: All analysis happens locally within the AI assistant
- **No Tracking**: No usage analytics or telemetry
- **Your Data Stays Yours**: Complete privacy for sensitive decisions

## ⚠️ Important Limitations

This skill has important limitations you should understand:

1. **Not Deterministic**: It won't tell you definitively what to do
2. **Quality Dependent**: Analysis quality depends on input quality (garbage in, garbage out)
3. **No Moral Judgment**: Frameworks are amoral - they don't evaluate ethics
4. **Context Blind**: AI doesn't know your full life context
5. **Quantification Limits**: Not everything can be scored numerically
6. **No Guarantee**: Following framework recommendations doesn't guarantee success

**Remember**: This skill provides analysis, not answers. The final decision is always yours, informed by these perspectives.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug or have a suggestion? Open an issue
2. **Improve Frameworks**: Submit PRs to enhance framework methodologies
3. **Add Translations**: Help translate the skill into other languages
4. **Share Examples**: Share how you've used the skill (anonymously)

### Development Setup
```bash
# Clone the repository
git clone https://github.com/noangel2014/decision-evaluation-skill.git

# Navigate to the skill directory
cd decision-evaluation-skill

# Make your changes and test
# Submit a pull request
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by systematic decision-making methodologies
- Built on proven analytical frameworks from business and psychology
- Designed for AI-native decision support

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/noangel2014/decision-evaluation-skill/issues)
- **Discussions**: [GitHub Discussions](https://github.com/noangel2014/decision-evaluation-skill/discussions)
- **Documentation**: Full documentation available in the `references/` directory

## 🗺️ Roadmap

- [ ] Add quick analysis mode (3 frameworks instead of 7)
- [ ] Support for custom framework selection
- [ ] Multi-language support
- [ ] Decision history tracking (optional, privacy-focused)
- [ ] Export reports to PDF/Markdown
- [ ] Integration with popular note-taking apps

---

**Made with ❤️ for better decision-making**

*Remember: The best decision is an informed decision. Use this skill as one input among many in your decision-making process.*
