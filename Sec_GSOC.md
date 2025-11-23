# Projects Similar to CodeGuard (Security & Static Analysis)

Since you are contributing to CodeGuard (a security and static analysis tool), here are **20 Open Source Projects** in the same domain. These are **active**, **contributor-friendly**, and mostly written in **Python**, making them perfect for your skill set.

## Top Tier: Direct Alternatives / Similar Tech
These projects do exactly what CodeGuard does: scan code for issues.

### 1. Bandit
**Focus:** Python Security Linter.
**Why:** It finds common security issues in Python code (hardcoded passwords, weak crypto). Exactly like CodeGuard's mission.
**Tech:** Python.
**Repo:** `PyCQA/bandit`

### 2. Pylint
**Focus:** Code Analysis & Linter.
**Why:** The gold standard for Python static analysis. Huge community.
**Tech:** Python.
**Repo:** `pylint-dev/pylint`

### 3. Checkov
**Focus:** Infrastructure as Code (IaC) Security.
**Why:** Scans Terraform, Kubernetes, and Dockerfiles for security misconfigurations.
**Tech:** Python.
**Repo:** `bridgecrewio/checkov`

### 4. Semgrep
**Focus:** Polyglot Static Analysis.
**Why:** Uses "rules" to find bugs. You can write your own rules (like CodeGuard rules).
**Tech:** Python (CLI), OCaml (Core).
**Repo:** `returntocorp/semgrep`

### 5. Detect-Secrets
**Focus:** Secret Scanning.
**Why:** Specifically finds hardcoded credentials. CodeGuard has a rule for this; this tool is dedicated to it.
**Tech:** Python.
**Repo:** `Yelp/detect-secrets`

## Cloud Security & Compliance
These tools scan cloud environments, similar to how CodeGuard scans code.

### 6. Cloud Custodian
**Focus:** Cloud Governance & Rules Engine.
**Why:** You write YAML policies (rules) to manage cloud resources. Very active CNCF project.
**Tech:** Python.
**Repo:** `cloud-custodian/cloud-custodian`

### 7. Prowler
**Focus:** AWS Security Best Practices.
**Why:** Scans AWS accounts against security standards (CIS, GDPR).
**Tech:** Python.
**Repo:** `prowler-cloud/prowler`

### 8. ScoutSuite
**Focus:** Multi-Cloud Security Auditing.
**Why:** assessing the security posture of cloud environments.
**Tech:** Python.
**Repo:** `nccgroup/ScoutSuite`

## Vulnerability Management
Tools to manage the findings from tools like CodeGuard.

### 9. DefectDojo
**Focus:** Vulnerability Management.
**Why:** It aggregates findings from other tools. If CodeGuard finds a bug, it goes here.
**Tech:** Python (Django).
**Repo:** `DefectDojo/django-DefectDojo`

### 10. OWASP PySec (Python Security)
**Focus:** Hardened Python Environment.
**Why:** OWASP is the main body for web security. Great place to learn.
**Tech:** Python.
**Repo:** `OWASP/www-project-python-security`

## Specialized Linters & Formatters
Tools that enforce specific quality standards.

### 11. SQLFluff
**Focus:** SQL Linter.
**Why:** CodeGuard checks for SQL injection; SQLFluff checks SQL style and correctness.
**Tech:** Python.
**Repo:** `sqlfluff/sqlfluff`

### 12. Black
**Focus:** The Uncompromising Code Formatter.
**Why:** Enforces strict style. Very high profile project.
**Tech:** Python.
**Repo:** `psf/black`

### 13. Ruff
**Focus:** Extremely Fast Linter.
**Why:** The new hotness in Python tooling. Written in Rust but has Python bindings.
**Tech:** Rust/Python.
**Repo:** `astral-sh/ruff`

### 14. Yamllint
**Focus:** YAML Linter.
**Why:** Essential for checking config files (CI/CD, Kubernetes).
**Tech:** Python.
**Repo:** `adrienverge/yamllint`

### 15. Ansible-Lint
**Focus:** Ansible Playbook Linter.
**Why:** Checks automation scripts for best practices.
**Tech:** Python.
**Repo:** `ansible/ansible-lint`

## Educational & Research
Projects to learn offensive/defensive security.

### 16. PyGoat
**Focus:** Vulnerable Python App.
**Why:** Intentionally insecure app to practice finding bugs (like the ones CodeGuard fixes).
**Tech:** Python (Django).
**Repo:** `adeyosemanputra/pygoat`

### 17. OWASP Honeypot
**Focus:** Deception Security.
**Why:** Traps attackers. Interesting Python networking project.
**Tech:** Python.
**Repo:** `OWASP/HoneyPot`

### 18. Gitleaks
**Focus:** Git Secret Scanner.
**Why:** Scans git history for secrets. (Go-based, but essential knowledge).
**Tech:** Go.
**Repo:** `gitleaks/gitleaks`

### 19. Safety
**Focus:** Dependency Security.
**Why:** Checks your `requirements.txt` for known vulnerable packages.
**Tech:** Python.
**Repo:** `pyupio/safety`

### 20. Radon
**Focus:** Code Metrics.
**Why:** Calculates Cyclomatic Complexity. Helps find "complex" code that needs refactoring.
**Tech:** Python.
**Repo:** `rubik/radon`

---

### Recommendation for You
Since you are working on **CodeGuard**, I highly recommend looking at **Bandit** (#1) and **Cloud Custodian** (#6).
- **Bandit** is the closest cousin to CodeGuard (Python security static analysis).
- **Cloud Custodian** uses a "Rules Engine" approach which is very similar to how you might define checks.
