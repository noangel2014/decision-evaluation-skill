---
name: decision-evaluation
description: Evaluate important decisions through 7 professional analytical frameworks (cost-benefit, SWOT, decision matrix, ICE, risk-reward, Eisenhower matrix, regret minimization) to help users examine career choices, financial decisions, life planning, and other major decisions from multiple dimensions. This skill applies to scenarios requiring systematic analysis of complex decisions.
---

# Decision Evaluation Framework

Evaluate important decisions through seven professional analytical frameworks to gain multi-dimensional insights into career choices, financial decisions, life planning, and other major choices.

## Purpose

This skill helps examine important decisions from multiple objective perspectives. It does NOT tell you what to do, but rather:

- Illuminate different aspects of your decision
- Reveal trade-offs and considerations you might have missed
- Provide objective scoring across multiple dimensions
- Help you think more clearly about complex choices

## When to Use This Skill

Invoke this skill when:

- User faces an important decision requiring systematic analysis
- Decisions involve career choices, financial investments, or life planning
- User wants to evaluate a decision from multiple objective perspectives
- Complex trade-offs exist that need to be illuminated
- User asks for help analyzing or evaluating a decision

**Trigger phrases**:
- "Help me analyze this decision"
- "Evaluate this choice"
- "Should I do X or Y?"
- "I need to make a decision about..."
- "Help me think through this choice"

## Workflow

### Step 1: Collect Decision Information

Guide the user to describe their decision with key details:

**Essential Information**:
- **Decision summary**: What is the core decision to be made?
- **Background context**: How did this situation arise? Why is it important?
- **Options being considered**: What are the possible choices?
- **Key considerations**: What factors matter most? (financial, time, personal, strategic, relationships)
- **Constraints**: What are the limitations or requirements?
- **Goals and values**: What are you trying to achieve? What matters most?

**Optional - Use Decision Template**:
For complex decisions, suggest using the structured template at `references/decision-template.md` to ensure comprehensive information gathering.

### Step 2: Run Framework Analysis

Analyze the decision using **seven independent frameworks**:

1. **Cost-Benefit Analysis** (`references/cost-benefit-analysis.md`)
   - Quantifies all costs against all benefits
   - Calculates ROI and net value
   - Best for: Financial decisions, resource allocation

2. **SWOT Analysis** (`references/swot-analysis.md`)
   - Examines Strengths, Weaknesses, Opportunities, Threats
   - Strategic positioning assessment
   - Best for: Career moves, competitive situations

3. **Decision Matrix** (`references/decision-matrix.md`)
   - Multi-criteria weighted evaluation
   - Objective scoring across prioritized factors
   - Best for: Complex multi-factor decisions

4. **ICE Framework** (`references/ice-framework.md`)
   - Impact, Confidence, Ease scoring
   - Quick prioritization and opportunity assessment
   - Best for: Resource-constrained choices

5. **Risk-Reward Assessment** (`references/risk-reward-assessment.md`)
   - Compares potential gains vs losses with probabilities
   - Evaluates asymmetric risk/reward profiles
   - Best for: High-stakes decisions, investments

6. **Eisenhower Matrix** (`references/eisenhower-matrix.md`)
   - Importance and urgency prioritization
   - Time management and action prioritization
   - Best for: Prioritization, time-sensitive decisions

7. **Regret Minimization** (`references/regret-minimization.md`)
   - Projects future regret at 1, 5, 10+ years
   - Long-term perspective and values alignment
   - Best for: Life-changing decisions, values-based choices

**Analysis Process**:

Analyze each framework one by one in a single response:

```
For each framework (1 through 7):
1. Read the framework guide from references/[framework-filename].md
2. Apply the framework to the user's decision
3. Generate detailed analysis with 0-100 score
4. Append to the growing report
5. Move to next framework

After all frameworks complete:
- Generate synthesis and summary
- Present the comprehensive report in the conversation
```

**Critical Requirements**:
- Each framework must be **independent** - no cross-influence during analysis
- Each framework produces a **detailed analysis** AND a **0-100 score**
- Follow framework guides **exactly** as written in reference files
- All results are aggregated into **ONE comprehensive report** (not separate files)

### Step 3: Aggregate Results

Combine all seven framework analyses into **ONE comprehensive report** and present it in the conversation:

**Output Method**: Present the complete analysis in the chat/conversation, NOT as separate files.

**Output Structure**:

```markdown
# Decision Analysis Report

**Decision**: [Name/title of decision]
**Analysis Date**: [ISO timestamp]

---

## Decision Being Evaluated

[Full description of the decision from user input]

---

## Framework Analysis Results

### 1. Cost-Benefit Analysis
**Score**: [X]/100

[Full report from framework]

---

### 2. SWOT Analysis
**Score**: [X]/100

[Full report from framework]

---

### 3. Decision Matrix (Weighted Criteria)
**Score**: [X]/100

[Full report from framework]

---

### 4. ICE Framework
**Score**: [X]/100

[Full report from framework]

---

### 5. Risk-Reward Assessment
**Score**: [X]/100

[Full report from framework]

---

### 6. Eisenhower Matrix
**Score**: [X]/100

[Full report from framework]

---

### 7. Regret Minimization Framework
**Score**: [X]/100

[Full report from framework]

---

## Summary Dashboard

| Framework | Score | Key Insight |
|-----------|-------|-------------|
| Cost-Benefit Analysis | [X]/100 | [1 sentence summary] |
| SWOT Analysis | [X]/100 | [1 sentence summary] |
| Decision Matrix | [X]/100 | [1 sentence summary] |
| ICE Framework | [X]/100 | [1 sentence summary] |
| Risk-Reward Assessment | [X]/100 | [1 sentence summary] |
| Eisenhower Matrix | [X]/100 | [1 sentence summary] |
| Regret Minimization | [X]/100 | [1 sentence summary] |

## Score Distribution

- **Highest Score**: [Framework name] ([Score]/100)
- **Lowest Score**: [Framework name] ([Score]/100)
- **Score Range**: [Highest - Lowest]
- **Agreement Level**: [High/Medium/Low based on score consistency]

## Framework Consensus

**Frameworks supporting this decision** (score ≥ 60):
- [Framework name]: [score]
- [Framework name]: [score]

**Frameworks opposing this decision** (score < 40):
- [Framework name]: [score]
- [Framework name]: [score]

**Frameworks neutral** (score 40-60):
- [Framework name]: [score]

## Key Insights

### When Frameworks Agree (High Consensus)
Multiple frameworks scoring similarly indicates:
- Clear-cut decision
- Consistent factors across dimensions
- Higher confidence in the direction

### When Frameworks Disagree (Low Consensus)
Frameworks with divergent scores indicate:
- Complex trade-offs
- Different priorities matter
- Need for deeper reflection on values
- Context-dependent decision

### Pay Special Attention To

1. **Extreme scores** (very high or very low) - reveal strong signals
2. **Regret Minimization** - often provides the clearest long-term perspective
3. **Risk-Reward** - critical for understanding downside exposure
4. **Your gut reaction** - which frameworks resonate with your intuition?

## User Guidance

This analysis is complete. Review each framework's detailed analysis to understand different perspectives on your decision. Pay special attention to:

1. Frameworks with extreme scores (very high or very low)
2. Areas of disagreement between frameworks
3. Insights that resonate most with your values
4. Factors you hadn't considered

**Remember**: This framework provides analysis, not answers. The final decision is yours, informed by these perspectives.
```

### Step 4: Provide Interpretation and Guidance

After presenting the comprehensive report, offer:

1. **Consensus Analysis**: What do most frameworks agree on?
2. **Key Trade-offs**: What are the main conflicts between frameworks?
3. **Decision Support**: Based on the analysis, what considerations should guide the final choice?
4. **Follow-up Questions**: Help the user reflect on which insights resonate most

## Framework Reference Guide

Quick reference for when each framework is most relevant:

| Framework | Best For | Key Output |
|-----------|----------|------------|
| Cost-Benefit | Financial viability, ROI | Economic score, cost-benefit ratio |
| SWOT | Strategic positioning | Strategic position assessment |
| Decision Matrix | Multi-factor comparison | Weighted criteria score |
| ICE | Quick prioritization | Impact × Confidence × Ease |
| Risk-Reward | High-stakes decisions | Risk-reward ratio, expected value |
| Eisenhower | Time/priority management | Quadrant placement, action priority |
| Regret Minimization | Life-changing decisions | Long-term regret projection |

## Critical Rules

**DO**:
- Run all seven frameworks in parallel for efficiency
- Keep frameworks independent - no cross-influence
- Follow framework guides exactly as written
- Preserve individual scores - DO NOT create composite scores
- Be thorough and honest in applying each framework
- Use the exact output format specified in each framework guide

**DO NOT**:
- Create composite or average scores across frameworks
- Modify framework scoring methodologies
- Skip or abbreviate framework analysis
- Let one framework influence another
- Make recommendations that override framework outputs

## Best Practices

**For Quality**:
- Encourage users to provide detailed decision context
- More detail leads to better analysis
- Apply frameworks rigorously, not superficially

**For Usefulness**:
- The value is in seeing how different analytical lenses reveal different aspects
- Help users synthesize perspectives with their own judgment and values
- Remind users that frameworks inform but don't make the decision

**For Interpretation**:
- Focus on areas of agreement and disagreement
- Highlight extreme scores and what they reveal
- Help users identify which insights resonate most

## Philosophy

Good decisions come from examining choices through multiple lenses. Each framework illuminates different aspects:

- **Cost-Benefit** focuses on efficiency and value
- **SWOT** focuses on strategic positioning
- **Decision Matrix** focuses on prioritized criteria
- **ICE** focuses on achievability and impact
- **Risk-Reward** focuses on asymmetry and probabilities
- **Eisenhower** focuses on time and importance
- **Regret Minimization** focuses on long-term perspective

The user's job is to synthesize these perspectives with their own judgment, values, and context to make the best decision for THEM.

## Limitations

This framework has important limitations:

- **Not deterministic**: It won't tell you definitively what to do
- **Garbage in, garbage out**: Analysis quality depends on input quality
- **No moral judgments**: Frameworks are amoral - they don't evaluate ethics
- **Context-blind**: AI doesn't know your full life context
- **Quantification limits**: Not everything can be scored numerically
- **No guarantee**: Following framework recommendations doesn't guarantee success

## Example Usage

**User**: "I'm trying to decide whether to take a job offer at a startup or stay at my current company."

**Assistant**: "I'll help you analyze this career decision through seven professional frameworks. Let me gather some information first...

[Collects decision details]

Now I'll run seven parallel analyses using Cost-Benefit, SWOT, Decision Matrix, ICE, Risk-Reward, Eisenhower, and Regret Minimization frameworks...

[Launches 7 parallel subagents]

Here's your comprehensive decision analysis...

[Presents full report with all framework analyses and synthesis]

Based on the analysis, most frameworks suggest [pattern]. However, note that [framework X] and [framework Y] disagree on [aspect]. This indicates [interpretation]..."

---

**Remember**: This skill provides structured analysis to illuminate decisions from multiple perspectives. The final choice always belongs to the user, informed by these insights and their own values and judgment.
