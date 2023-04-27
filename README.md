# Tools for implementing DevSecOps

## Development
1. GitSecrets - Used to identify any personal tokens or security credentials that have been mistakenly committed to source code by mistake
2. Security Plugins in IDEs (Snyk, VeraCode, Fortify have plugins in VSCode) ; Shift-Left approach
3. Trufflehog - GitSecrets w/ Enterprise license

## Security
1. Code Quality Tool (Sonarqube)
2. SAST Security Tools (Fortify, Veracode, Checkmarx)
3. SCA Security Tools (Fortify, Veracode, Blackduck, Snyk)
4. DAST Security Tools (OWASP Zap, WebInspect, Veracode DAST, Acunetix)
5. IAC Security Tools (Bridgecrew, Snyk) - IAC is widely used b/c on the cloud most infra is created by code
6. Container Security Tools (Aqua Qualys, PrismaCloud)

## Operations
1. Build Pipeline Tools (Jenkins, AWS, GCP Cloudbuild, Azure DevOps, GitHub Actions, GitLab)
2. Cloud Security Posture Management Tools (AQUA, BridgeCrew)
3. Container Registry Scanning Tools (AQUA, AWS Native Registry Scanning)
4. Infrastructure Scanning Tools (ChefInspect(Compliance), Nessus)
5. Cloud Security Tools (AWS Security Hub, Azure Defender)

