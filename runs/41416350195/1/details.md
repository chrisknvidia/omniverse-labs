# SkillEvaluator evaluation report

**Tier 1 scan result: INCOMPLETE**

1 skills · 0 passed · 0 failed · 1 incomplete

Errors: 1 · Warnings: 13

## Evaluation scope

Tier 1: executed for 1/1 skills with validator evidence; result INCOMPLETE\. Tier 2: Not run\. Tier 3: Not run\.

Recorded LLM stages: skipped\. LLM checks disabled by \-\-no\-llm\.

Static scanner outcomes do not establish behavioral usefulness. Not run tiers are not passes.

[Open full report](https://chrisknvidia.github.io/omniverse-labs/runs/41416350195/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/omniverse-labs/actions/runs/41416350195)

**CI run conclusion:** failure

**Commit:** a84f64237816715923f7f77ce52b02e98af83b05

**Runtime image:** ghcr\.io/chrisknvidia/skillevaluator\-ci\-demo@​sha256:b55085bdfee17a0004dcb6330745ecbae029ab16887a2e81bfac7b7f1c9212c3

## Needs attention

**projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography / Security Scan (INCOMPLETE):** skillspector JSON field 'analysis\_completeness' reports incomplete analysis \(status 'partial'\); security scan did not complete

## Skills and scores

| Skill | Tier 1 | Quality / 100 | Grade | Errors | Warnings |
| --- | --- | --- | --- | --- | --- |
| projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography | INCOMPLETE | 90.8 | A | 1 | 13 |

## projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography

[Skill details](https://chrisknvidia.github.io/omniverse-labs/runs/41416350195/1/index.html#skill-001) · [Native HTML](https://chrisknvidia.github.io/omniverse-labs/runs/41416350195/1/skill-001/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/omniverse-labs/runs/41416350195/1/skill-001/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 90 | 0\.35 | 2 |
| discoverability | 95 | 0\.25 | 1 |
| reliability | 85 | 0\.25 | 3 |
| efficiency | 95 | 0\.15 | 1 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | PASS | 8 | 0 | 4 |
| Semantic Version Validation | NOT APPLICABLE | 1 | 0 | 0 |
| Security Scan | INCOMPLETE | 0 | 1 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 1 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | PASS | 1 | 0 | 7 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md"\}

**Evidence: frontmatter\_valid:** Valid frontmatter for skill 'agentic\-codebase\-cartography'

**Evidence metadata:** \{"description\_length": 282\}

**Evidence: naming\_convention:** Folder name 'agentic\-codebase\-cartography' follows kebab\-case convention

**Evidence metadata:** \{"name\_length": 28\}

**Evidence: line\_count:** SKILL\.md within line limit \(83/500\)

**Evidence metadata:** \{"limit": 500, "line\_count": 83\}

**Evidence: body\_heading:** Body contains a top\-level heading

**Evidence: optional\_files:** Found optional supporting files: agents

**Evidence metadata:** \{"files\_found": \["agents"\]\}

**Evidence: name\_consistency:** Directory name matches frontmatter: 'agentic\-codebase\-cartography'

**Evidence: author\_format:** Valid author format: SkillEvaluator integration test &lt;ci\-demo@​example\.com&gt;

**Finding: folder\_hierarchy \(medium\):** Skill not in standard location \(skills/ or team\-skills/\)

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography

**Suggested fix:** Move skill to skills/&lt;skill\-name&gt;/ or team\-skills/&lt;team&gt;/&lt;skill\-name&gt;/

**Finding: body\_recommended\_section \(medium\):** Missing recommended section: '\#\# Instructions'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Consider adding a '\#\# Instructions' or '\#\# Usage' section\. Per agentskills\.io the body format is unrestricted, so this is a convention nudge — it also gives the quality scorer a stable anchor for instruction\-quality heuristics\.

**Finding metadata:** \{"missing\_section": "\#\# Instructions"\}

**Finding: body\_recommended\_section \(medium\):** Missing recommended section: '\#\# Examples'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Consider adding a '\#\# Examples' section\. If examples are already inline under instructions, this can be skipped\.

**Finding metadata:** \{"missing\_section": "\#\# Examples"\}

**Warning:** \[SCHEMA\-MEDIUM\] Skill not in standard location \(skills/ or team\-skills/\) in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography

**Warning:** \[SCHEMA\-MEDIUM\] Missing recommended section: '\#\# Instructions' in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[SCHEMA\-MEDIUM\] Missing recommended section: '\#\# Examples' in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

**Scanner message:** \[OK\] frontmatter\_valid: Valid frontmatter for skill 'agentic\-codebase\-cartography'

**Scanner message:** \[OK\] naming\_convention: Folder name 'agentic\-codebase\-cartography' follows kebab\-case convention

**Scanner message:** \[OK\] line\_count: SKILL\.md within line limit \(83/500\)

**Scanner message:** \[OK\] body\_heading: Body contains a top\-level heading

**Scanner message:** \[OK\] optional\_files: Found optional supporting files: agents

**Scanner message:** \[OK\] name\_consistency: Directory name matches frontmatter: 'agentic\-codebase\-cartography'

**Scanner message:** \[OK\] author\_format: Valid author format: SkillEvaluator integration test &lt;ci\-demo@​example\.com&gt;

### Semantic Version Validation — evidence

**Evidence: version\_optional:** No semantic version label present; resource will use commit\-hash history

**Evidence metadata:** \{"previous\_version": null\}

**Scanner message:** \[OK\] version\_optional: No semantic version label present; resource will use commit\-hash history

### Security Scan — evidence

**Error:** skillspector JSON field 'analysis\_completeness' reports incomplete analysis \(status 'partial'\); security scan did not complete

**Incomplete scanners:** \["skillspector"\]

### PII Scan — evidence

**Evidence: pii\_scan\_start:** Scanning 2 files for PII

**Evidence metadata:** \{"file\_count": 2\}

**Evidence: pii\_detection:** No PII detected in 2 files \(emails, SSNs, phone numbers, paths\)

**Evidence metadata:** \{"files\_scanned": 2\}

**Scanner message:** \[OK\] pii\_scan\_start: Scanning 2 files for PII

**Scanner message:** \[OK\] pii\_detection: No PII detected in 2 files \(emails, SSNs, phone numbers, paths\)

### License Compliance — evidence

**Evidence: license\_compliance:** License compliance scan completed \(not detected\)

**Evidence metadata:** \{"license\_status": "not\_detected"\}

**Warning:** No license information found \- manual review required\. Add a LICENSE file or 'license' field in frontmatter\.

**Scanner message:** No license detected in any tier

**Scanner message:** \[OK\] license\_compliance: License compliance scan completed \(not detected\)

### Code Risk Analysis — evidence

**Evidence: code\_file\_discovery:** No code files found \- code risk analysis is not applicable

**Evidence metadata:** \{"file\_counts": \{"js": 0, "py": 0, "sh": 0\}\}

**Scanner message:** \[OK\] code\_file\_discovery: No code files found \- code risk analysis is not applicable

### Secrets Detection — evidence

**Evidence: gitleaks:** No secrets detected by Gitleaks

**Scanner message:** \[OK\] gitleaks: No secrets detected by Gitleaks

### Code Integrity &amp; Hygiene — evidence

**Evidence: dead\_links\_scan:** Checking 1 markdown files for dead links

**Evidence metadata:** \{"file\_count": 1\}

**Evidence: dead\_links:** All relative links valid in 1 markdown file\(s\)

**Evidence metadata:** \{"files\_checked": 1\}

**Evidence: dependencies:** No dependency files found \(requirements\.txt, pyproject\.toml\)

**Evidence: test\_discovery:** No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

**Evidence metadata:** \{"coverage\_measured": false, "execution\_performed": false, "patterns": \["test\_\*\.py", "\*\_test\.py"\], "test\_count": 0\}

**Warning:** No standard Python test\-file candidates found; consider adding tests

**Scanner message:** \[OK\] dead\_links\_scan: Checking 1 markdown files for dead links

**Scanner message:** \[OK\] dead\_links: All relative links valid in 1 markdown file\(s\)

**Scanner message:** \[OK\] dependencies: No dependency files found \(requirements\.txt, pyproject\.toml\)

**Scanner message:** \[OK\] test\_discovery: No standard Python test\-file candidates found; target tests were not executed and coverage was not measured\. Consider adding tests\.

### Dependency Vulnerability Audit — evidence

**Evidence: dependency\_file\_discovery:** No dependency files found \- vulnerability audit is not applicable

**Scanner message:** \[OK\] dependency\_file\_discovery: No dependency files found \- vulnerability audit is not applicable

### Unicode Smuggling Detection — evidence

**Evidence: unicode\_scan:** No invisible Unicode characters detected in 2 file\(s\)

**Evidence metadata:** \{"files\_scanned": 2\}

**Scanner message:** \[OK\] unicode\_scan: No invisible Unicode characters detected in 2 file\(s\)

### QUALITY — evidence

**Evidence: quality\_score:** Score: 90\.8/100 \(Grade: A\)

**Evidence metadata:** \{"grade": "A", "overall\_score": 90\.8, "skill\_type": "guide\-only"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'version'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Add 'version' to frontmatter — Semantic version \(e\.g\., "1\.0\.0"\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'metadata\.tags'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Add 'tags' under metadata: — Categorization tags \(under metadata:, list of 1\-5 items\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Finding: quality\_discoverability \(low\):** Description very long \(282 chars, recommend 50\-150\)

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Keep descriptions concise for progressive disclosure

**Finding metadata:** \{"deduction": 5, "dimension": "discoverability"\}

**Finding: quality\_reliability \(low\):** No prerequisites/requirements documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Document dependencies, API keys, or setup needed

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Finding: quality\_reliability \(low\):** No limitations documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Add '\#\# Limitations' section with known issues/constraints

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Finding: quality\_reliability \(low\):** No troubleshooting section documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Add '\#\# Troubleshooting' with Error/Cause/Solution patterns

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Finding: quality\_efficiency \(low\):** Uses complex/corporate language

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Suggested fix:** Use simple, direct language: 'use' not 'utilize'

**Finding metadata:** \{"deduction": 5, "dimension": "efficiency"\}

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'version' in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'metadata\.tags' in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-LOW\] Description very long \(282 chars, recommend 50\-150\) in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No prerequisites/requirements documented in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No limitations documented in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No troubleshooting section documented in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Warning:** \[QUALITY\-LOW\] Uses complex/corporate language in /workspace/projects/nanousd\-labs/agentic\-skills/agentic\-codebase\-cartography/SKILL\.md

**Scanner message:** \[OK\] quality\_score: Score: 90\.8/100 \(Grade: A\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

[Open full report](https://chrisknvidia.github.io/omniverse-labs/runs/41416350195/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/omniverse-labs/actions/runs/41416350195)
