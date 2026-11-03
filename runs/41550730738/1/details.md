# SkillEvaluator evaluation report

**Tier 1 scan result: FAILED**

1 skills · 0 passed · 1 failed · 0 incomplete

Errors: 2 · Warnings: 10

## Evaluation scope

Tier 1: executed for 1/1 skills with validator evidence; result FAILED\. Tier 2: Not run\. Tier 3: Not run\.

Recorded LLM stages: skipped\. LLM checks disabled by \-\-no\-llm\.

Static scanner outcomes do not establish behavioral usefulness. Not run tiers are not passes.

[Open full report](https://chrisknvidia.github.io/omniverse-labs/runs/41550730738/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/omniverse-labs/actions/runs/41550730738)

**CI run conclusion:** failure

**Commit:** fd08eb5b64c6ee1502c8fdf504e927a666d0754d

**Runtime image:** ghcr\.io/nvidia/skillevaluator\-tier1@​sha256:c75c826f0e52d6c9a8d303ad7eefd606ed86e6940123f42b4eda2457863bcee7

## Needs attention

**projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi / Schema &amp; Repository Governance (FAIL):** Field 'name': Value error, Skill name 'INVALID NAME' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\)

Location: /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

Suggested fix: Fix the 'name' field in frontmatter according to schema requirements

**projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi / QUALITY (FAIL):** Invalid name format: 'INVALID NAME' \(lowercase/numbers/hyphens only\)

Location: /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

Suggested fix: Use only lowercase letters, numbers, and hyphens

## Skills and scores

| Skill | Tier 1 | Quality / 100 | Grade | Errors | Warnings |
| --- | --- | --- | --- | --- | --- |
| projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi | FAIL | 84.5 | B | 2 | 10 |

## projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi

[Skill details](https://chrisknvidia.github.io/omniverse-labs/runs/41550730738/1/index.html#skill-001) · [Native HTML](https://chrisknvidia.github.io/omniverse-labs/runs/41550730738/1/skill-001/skillevaluator-tier1.html) · [JSON](https://chrisknvidia.github.io/omniverse-labs/runs/41550730738/1/skill-001/skillevaluator-tier1.json)

### Recorded quality dimensions

| Dimension | Score / 100 | Weight | Issues |
| --- | --- | --- | --- |
| correctness | 70 | 0\.35 | 4 |
| discoverability | 95 | 0\.25 | 1 |
| reliability | 85 | 0\.25 | 3 |
| efficiency | 100 | 0\.15 | 0 |

### Validator outcomes

| Validator | Outcome | Checks recorded | Errors | Warnings |
| --- | --- | --- | --- | --- |
| Schema &amp; Repository Governance | FAIL | 1 | 1 | 1 |
| Semantic Version Validation | NOT APPLICABLE | 1 | 0 | 0 |
| Security Scan | PASS | 1 | 0 | 0 |
| PII Scan | PASS | 2 | 0 | 0 |
| License Compliance | PASS | 1 | 0 | 1 |
| Code Risk Analysis | NOT APPLICABLE | 1 | 0 | 0 |
| Secrets Detection | PASS | 1 | 0 | 0 |
| Code Integrity &amp; Hygiene | PASS | 4 | 0 | 1 |
| Dependency Vulnerability Audit | NOT APPLICABLE | 1 | 0 | 0 |
| Unicode Smuggling Detection | PASS | 1 | 0 | 0 |
| QUALITY | FAIL | 1 | 1 | 7 |
| SCRIPT\_LINT | NOT APPLICABLE | 1 | 0 | 0 |

### Schema &amp; Repository Governance — evidence

**Evidence: manifest\_exists:** Found skill manifest: SKILL\.md

**Evidence metadata:** \{"file\_path": "/workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md"\}

**Finding: frontmatter\_field \(high\):** Field 'name': Value error, Skill name 'INVALID NAME' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\)

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Fix the 'name' field in frontmatter according to schema requirements

**Finding metadata:** \{"error\_type": "value\_error", "field": "name"\}

**Error:** \[SCHEMA\-HIGH\] Field 'name': Value error, Skill name 'INVALID NAME' must be in kebab\-case format \(lowercase letters, numbers, and hyphens only, starting with a letter\) in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** Workflow scope: llm skipped\. LLM checks disabled by \-\-no\-llm\.

**Scanner message:** \[OK\] manifest\_exists: Found skill manifest: SKILL\.md

### Semantic Version Validation — evidence

**Evidence: version\_optional:** No semantic version label present; resource will use commit\-hash history

**Evidence metadata:** \{"previous\_version": null\}

**Scanner message:** \[OK\] version\_optional: No semantic version label present; resource will use commit\-hash history

### Security Scan — evidence

**Evidence: skillspector:** No security vulnerabilities detected \(secrets, API keys, credentials\)

**Scanner message:** \[OK\] skillspector: No security vulnerabilities detected \(secrets, API keys, credentials\)

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

**Evidence: quality\_score:** Score: 84\.5/100 \(Grade: B\)

**Evidence metadata:** \{"grade": "B", "overall\_score": 84\.5, "skill\_type": "guide\-only"\}

**Finding: quality\_correctness \(high\):** Invalid name format: 'INVALID NAME' \(lowercase/numbers/hyphens only\)

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Use only lowercase letters, numbers, and hyphens

**Finding metadata:** \{"deduction": 15, "dimension": "correctness"\}

**Finding: quality\_correctness \(low\):** No examples provided

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Add example usage with code blocks

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'version'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Add 'version' to frontmatter — Semantic version \(e\.g\., "1\.0\.0"\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Finding: quality\_correctness \(medium\):** SKILL\_SPEC recommended field missing: 'metadata\.tags'

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Add 'tags' under metadata: — Categorization tags \(under metadata:, list of 1\-5 items\)

**Finding metadata:** \{"deduction": 5, "dimension": "correctness"\}

**Finding: quality\_discoverability \(low\):** Description very long \(272 chars, recommend 50\-150\)

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Keep descriptions concise for progressive disclosure

**Finding metadata:** \{"deduction": 5, "dimension": "discoverability"\}

**Finding: quality\_reliability \(low\):** No prerequisites/requirements documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Document dependencies, API keys, or setup needed

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Finding: quality\_reliability \(low\):** No limitations documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Add '\#\# Limitations' section with known issues/constraints

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Finding: quality\_reliability \(low\):** No troubleshooting section documented

**File:** /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Suggested fix:** Add '\#\# Troubleshooting' with Error/Cause/Solution patterns

**Finding metadata:** \{"deduction": 5, "dimension": "reliability"\}

**Error:** \[QUALITY\-HIGH\] Invalid name format: 'INVALID NAME' \(lowercase/numbers/hyphens only\) in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No examples provided in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'version' in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-MEDIUM\] SKILL\_SPEC recommended field missing: 'metadata\.tags' in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-LOW\] Description very long \(272 chars, recommend 50\-150\) in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No prerequisites/requirements documented in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No limitations documented in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Warning:** \[QUALITY\-LOW\] No troubleshooting section documented in /workspace/projects/nanousd\-labs/agentic\-skills/contract\-first\-ffi/SKILL\.md

**Scanner message:** \[OK\] quality\_score: Score: 84\.5/100 \(Grade: B\)

### SCRIPT\_LINT — evidence

**Evidence: lint:** No scripts/ or tools/ directory found

**Scanner message:** \[OK\] lint: No scripts/ or tools/ directory found

[Open full report](https://chrisknvidia.github.io/omniverse-labs/runs/41550730738/1/index.html) · [Workflow run and logs](https://github.com/chrisknvidia/omniverse-labs/actions/runs/41550730738)
