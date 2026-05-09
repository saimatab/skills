# SQA Mock Interview Skills

Custom skills for Software Quality Assurance and Automation engineers.

## 📁 Repository Structure

```
skills/
├── README.md (this file)
└── SQAMockInterview/
    ├── SKILL.md (650 lines - Main skill documentation)
    ├── references/
    │   ├── questions.json (21 scenario-based interview questions)
    │   └── scoring_rubric.md (Evaluation criteria and scoring guide)
    └── evals/
        └── evals.json (Test cases for skill validation)
```

---

## 🎯 Available Skills

### /SQAMockInterview

A comprehensive mock interview skill for **SQAA (Software Quality AI Automation) engineers**. Conducts realistic, scenario-based interviews with real-time feedback and scoring.

**[→ View Full Skill Details](./SQAMockInterview/SKILL.md)**

#### Features

- ✅ **21 Scenario-Based Questions** across 8 QA domains
- ✅ **Smart Filtering** — Topic, difficulty level, company scale
- ✅ **Real-Time Feedback** — 1-5 scoring with actionable insights
- ✅ **Comprehensive Rubric** — Consistent evaluation criteria
- ✅ **Multiple Use Cases** — For candidates, interviewers, QA leads
- ✅ **Interview Summary** — Strengths, gaps, interview readiness

#### Domains Covered

1. **Test Automation** — Framework design, flaky tests, maintenance
2. **CI/CD** — Pipeline design, deployment strategies, environment parity
3. **API Testing** — REST APIs, contract testing, distributed systems
4. **QA Strategy** — Risk-based testing, shift-left, coverage decisions
5. **Test Data Management** — Data generation, privacy, isolation at scale
6. **Performance Testing** — Load testing, profiling, bottleneck identification
7. **Security Testing** — OWASP, penetration testing, compliance
8. **Test Leadership** — Team collaboration, communication, hiring

#### Usage

```
/SQAMockInterview [topic] [difficulty] [company-level] [num-questions]
```

**Examples:**

```
/SQAMockInterview test automation advanced FAANG 6
/SQAMockInterview CI/CD intermediate startup 4
/SQAMockInterview API testing beginner any 3
/SQAMockInterview any expert mixed 5
```

Or use natural language:
> "Give me advanced questions on QA strategy for an enterprise company"

---

## 📖 Skill Documentation

### SKILL.md
**Main skill file** (650 lines)

Contains:
- Complete overview of how the skill works
- Interview phases and workflow
- All 8 QA domains explained
- Scoring scale (1-5) with clear definitions
- Tips for effective answers
- Example Q&A walkthroughs
- Interview readiness assessment
- Timeline expectations

**[Read SKILL.md →](./SQAMockInterview/SKILL.md)**

### references/questions.json
**Question Bank** (21 questions)

Contains:
- 21 carefully curated scenario-based questions
- Organized by:
  - Topic (test automation, CI/CD, API testing, etc.)
  - Difficulty (beginner, intermediate, advanced, expert)
  - Company level (startup, scale-up, enterprise, FAANG)
- Evaluation criteria for each question
- Company context and expectations

**[View Questions →](./SQAMockInterview/references/questions.json)**

### references/scoring_rubric.md
**Evaluation Guide** (8 KB)

Contains:
- 1-5 scoring definitions
- Evaluation dimensions:
  - Technical Knowledge (35%)
  - Problem-Solving & Strategy (35%)
  - Communication & Collaboration (20%)
  - Industry Best Practices (10%)
- Domain-specific scoring notes
- Feedback templates
- Comparative assessment criteria

**[View Rubric →](./SQAMockInterview/references/scoring_rubric.md)**

### evals/evals.json
**Test Cases** (5 scenarios)

Contains validation test cases to ensure the skill works correctly for:
- FAANG advanced interviews
- Startup intermediate interviews
- Enterprise intermediate interviews
- Scale-up beginner interviews
- Mixed domain interviews

---

## 🚀 How to Use This Skill

### Option 1: In Claude Code (Desktop/IDE)

1. Click **Plugins** → **Browse Skills**
2. Search for `SQAMockInterview`
3. Click **Install**
4. Run: `/SQAMockInterview [your preferences]`

### Option 2: In Claude.ai (Web)

1. Visit [claude.ai/code](https://claude.ai/code)
2. Copy the skill from this repository
3. Install using the skill installer
4. Run: `/SQAMockInterview`

### Option 3: Manual Installation

1. Clone or download this repository
2. Copy the `SQAMockInterview/` folder to your Claude plugins directory
3. Restart Claude Code
4. Run: `/SQAMockInterview`

---

## 📊 Sample Questions

### Beginner Level (Test Automation)
> Your team is building an e-commerce website and needs to test the checkout flow. You're tasked with writing automated tests. What testing approach would you take, and what tools would you use?

### Intermediate Level (CI/CD)
> Your CI/CD pipeline is failing 30% of the time due to environment inconsistencies. Tests pass locally but fail in CI. What strategies would you use to achieve environment parity?

### Advanced Level (API Testing)
> Your system has microservices with eventual consistency. A create user request returns success, but the user might not be searchable for 2+ seconds. How do you test this reliably?

**[View All 21 Questions →](./SQAMockInterview/references/questions.json)**

---

## 🎓 Interview Readiness

After completing a mock interview, you'll receive:

- **Overall Score** — Average across all questions
- **Strengths** — Themes in your strong answers
- **Development Areas** — Consistent gaps to address
- **Interview Readiness** — How you'd likely perform in a real interview
- **Next Steps** — Specific topics to study

---

## ✨ Who Should Use This?

✅ **QA Engineers** preparing for interviews  
✅ **Test Automation Engineers** at any level  
✅ **Interviewers** needing interview question banks  
✅ **QA Leads** assessing team skills  
✅ **Career Switchers** entering QA/automation  
✅ **FAANG Candidates** preparing for tech interviews  

---

## 📝 Skill Specifications

| Aspect | Details |
|--------|---------|
| **Name** | SQAMockInterview |
| **Type** | Interactive Mock Interview |
| **Questions** | 21 scenario-based |
| **Domains** | 8 (automation, CI/CD, API, strategy, data, performance, security, leadership) |
| **Difficulty Levels** | 4 (beginner, intermediate, advanced, expert) |
| **Company Scales** | 4 (startup, scale-up, enterprise, FAANG) |
| **Scoring** | 1-5 scale with detailed rubric |
| **Time per Interview** | 30-50 minutes |
| **Use Cases** | Interview prep, skill assessment, hiring, team evaluation |

---

## 🔄 Versions

- **v1.1** (May 9, 2026) — Optimized description for better skill triggering
- **v1.0** (May 9, 2026) — Initial release with 21 questions and comprehensive rubric

---

## 📞 Support

For questions about using this skill:
1. Check the [SKILL.md documentation](./SQAMockInterview/SKILL.md)
2. Review the [scoring rubric](./SQAMockInterview/references/scoring_rubric.md)
3. Browse [example questions](./SQAMockInterview/references/questions.json)

---

## 📄 License

These skills are provided as-is for educational and interview preparation purposes.

---

**Last Updated:** May 9, 2026  
**Repository:** https://github.com/saimatab/skills  
**Status:** ✅ Active and Maintained
