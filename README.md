# 🔐 Security Pipelines

This repository serves as the central hub for reusable security-focused CI/CD pipelines. It is designed to be consumed by other repositories across the organization to ensure secure and compliant software delivery practices.

## 💡 Purpose
- Provide standardized security checks across all projects
- Automate vulnerability scanning and license checks
- Enforce static code analysis and secrets detection
- Integrate with GitHub Actions or other CI systems

## 📦 Features
- Trivy, OWASP ZAP, Snyk integration
- Reusable GitHub Actions workflows
- Secrets scanning
- License and dependency audits
- Pull request-based security feedback

## 🧩 Usage
Other repositories (like `sample-app`) can include these workflows via:
```yaml
uses: your-org/security-pipelines/.github/workflows/security.yml@main
