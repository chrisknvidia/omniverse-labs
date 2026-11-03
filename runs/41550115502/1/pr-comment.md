**Tier 1 scan result: FAILED**

23 skills · 0 passed · 23 failed · 0 incomplete

| Skill | Status | Quality / 100 |
| --- | --- | --- |
| projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography | FAIL | 89 / B |
| projects/nanousd\-labs/agentic\-skills/ai\-agent\-orchestration | FAIL | 89.8 / B |
| projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi | FAIL | 88 / B |
| projects/nanousd\-labs/agentic\-skills/graphics\-debugging\-lab | FAIL | 88 / B |
| projects/nanousd\-labs/agentic\-skills/layered\-boundary\-refactor | FAIL | 86.8 / B |

18 more skills are listed in the full report.

## What to fix

First issue per affected skill; the full report contains all findings.

**projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography**

Problem: Security Scan: skillspector JSON field 'analysis\_completeness' reports incomplete analysis \(status 'partial'\); security scan did not complete

Suggested fix: Check this validator's diagnostics and rerun after restoring the missing scan\.

**projects/nanousd\-labs/agentic\-skills/ai\-agent\-orchestration**

Problem: Security Scan: skillspector JSON field 'analysis\_completeness' reports incomplete analysis \(status 'partial'\); security scan did not complete

Suggested fix: Check this validator's diagnostics and rerun after restoring the missing scan\.

**projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi**

Problem: Author not specified in metadata

File: projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

Suggested fix: Add 'metadata\.author' field with format 'Name &lt;email@​example\.com&gt;'

**projects/nanousd\-labs/agentic\-skills/graphics\-debugging\-lab**

Problem: Author not specified in metadata

File: projects/nanousd\-labs/agentic\-skills/graphics\-debugging\-lab/SKILL\.md

Suggested fix: Add 'metadata\.author' field with format 'Name &lt;email@​example\.com&gt;'

**projects/nanousd\-labs/agentic\-skills/layered\-boundary\-refactor**

Problem: Author not specified in metadata

File: projects/nanousd\-labs/agentic\-skills/layered\-boundary\-refactor/SKILL\.md

Suggested fix: Add 'metadata\.author' field with format 'Name &lt;email@​example\.com&gt;'

**18 more affected skills:** open the full report.

Push your fixes to rerun PR checks, or rerun the workflow after resolving scan errors.

**CI run conclusion:** failure

Tier 1 static checks.

[Open full report](https://chrisknvidia.github.io/omniverse-labs/runs/41550115502/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/omniverse-labs/actions/runs/41550115502)
