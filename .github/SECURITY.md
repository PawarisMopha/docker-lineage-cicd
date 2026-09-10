# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please **DO NOT** create a public GitHub issue. Instead, please follow our responsible disclosure process:

### Private Vulnerability Reporting

1. **Use GitHub's Private Vulnerability Reporting**: https://github.com/PawarisMopha/docker-lineage-cicd/security/advisories/new
2. **Email us** (if preferred): Include [SECURITY] in the subject line
3. **Provide details**:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if you have one)

We will acknowledge your report within 48 hours and work with you to understand and resolve the issue.

## Supported Versions

| Version | Supported | Security Updates |
|---------|-----------|------------------|
| Latest  | ✅ Yes    | Immediate        |
| v1.x    | ✅ Yes    | Within 7 days    |
| < v1.0  | ❌ No     | None             |

## Security Features Enabled

This project has the following security measures in place:

### 🔍 Code Analysis
- ✅ **CodeQL** - Static code analysis
- ✅ **Semgrep** - Pattern-based SAST
- ✅ **Bandit** - Python security linting
- ✅ **ShellCheck** - Shell script analysis

### 🚀 Container Security
- ✅ **Trivy** - Vulnerability scanning
- ✅ **Grype** - Software bill of materials
- ✅ **Checkov** - Infrastructure as Code scanning
- ✅ **Dockle** - Container linter
- ✅ **Hadolint** - Dockerfile linting

### 🔐 Secret Management
- ✅ **TruffleHog** - Secrets detection
- ✅ **GitGuardian** - Secret scanning
- ✅ **GitHub Push Protection** - Blocks commits with secrets
- ✅ **Dependabot** - Dependency vulnerability alerts

### 📦 Dependency Management
- ✅ **Dependabot** - Automated dependency updates
- ✅ **Renovate** - Advanced dependency management
- ✅ **SBOM Generation** - Software bill of materials
- ✅ **License Compliance** - License checking

## Security Best Practices

When using this Docker image:

1. **Always pull from official sources**
   ```bash
   docker pull lineageos4microg/docker-lineage-cicd:latest
