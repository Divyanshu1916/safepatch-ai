<p align="center">
  <img src="SafePatch-AI-thumbnail.png"
       alt="SafePatch AI evidence-grounded software repair dashboard"
       width="100%">
</p>

Replace the default README.md with a professional, hackathon-ready README for SafePatch AI.

Remove all generic Google AI Studio starter text such as:
- “Built with AI Studio”
- “The fastest path from prompt to production”
- “Start building”

Create documentation with these sections:

1. Project title:
SafePatch AI — Evidence-Grounded Software Repair

2. Badges:
IBM Bob 2.0 Hackathon, Google AI Studio, Gemini, Responsible AI

3. One-line summary:
SafePatch AI analyzes repositories and bug reports to identify root causes, generate regression tests, highlight security risks, and require human approval before proposed repairs are accepted.

4. Problem
Explain hidden regressions, authorization failures, missing tests, and risks caused by rushed bug fixes.

5. Solution
Explain evidence-grounded repository analysis, root-cause detection, repair planning, security analysis, regression-test generation, and human approval.

6. Key Features
- Judge Demo Mode
- Repository-aware evidence
- File and line citations
- Cross-Tenant IDOR demonstration
- Behavior Comparison view
- Security risk analysis
- Regression-test generation
- Human Approval Gate
- Downloadable Markdown audit report
- IBM Bob 2.0 SDLC evidence

7. Demo Workflow
Repository and bug report → analysis → evidence → repair plan → regression tests → security review → human approval → audit report.

8. Architecture
React frontend → Node.js/Express backend → Gemini analysis → structured results → human approval and report export.

9. Technologies Used
- IBM Bob 2.0
- Google AI Studio
- Gemini
- React
- TypeScript
- Node.js
- Express
- Vite
- AST analysis
- Jest/Supertest
- Google Cloud Run

10. IBM Bob 2.0 Usage
Explain honestly that IBM Bob was used for architecture planning, multi-file implementation, debugging, refactoring, testing, security review, documentation, and deployment verification. Do not claim that IBM Bob is a runtime API in the application.

11. Security and Responsible AI
Explain:
- No arbitrary uploaded code execution
- API keys remain server-side
- AI recommendations are not automatically committed
- Evidence is separated from assumptions
- Human approval is required
- Limitations are disclosed

12. Running Locally
Include:
npm install
npm run dev

13. Production Build
Include:
npm run build
npm start

14. Demo Instructions
Explain how to click Load Demo, Judge Demo Mode, Judge View, review evidence, approve the repair plan, and download the audit report.

15. Project Metrics
Use only these verified demonstration metrics:
- 6 files analyzed
- 3 affected layers
- 3 regression-test suites synthesized
- 3 security risks flagged
- 98% confidence
- 1.42-second analysis duration
- 100% evidence-grounded citations

Clearly label them as demonstration metrics, not production benchmarks.

16. Limitations
Explain that proposed code changes are recommendations, uploaded code is not executed, and results depend on repository quality and available evidence.

17. License
Use a simple section stating that this is an IBM Bob 2.0 Hackathon prototype.

Use polished Markdown, clear headings, tables where helpful, and no unsupported claims. Make the README suitable for public GitHub review.
