## DevSecOps in GitLab

- GitHub has vulnerable code in repository
- Add Repo to GitLab Repository
- Add .gitlab-ci.yaml file to create GitLab + DevSecOps pipeline. Creates SAST, SCA, DAST tools using the .yaml
- GitLab CI/CD Pipelines will have logs
- Reports will be stored as artifacts in the piepline
- Pipeline Artifacts can be saved and downloaded to view results

--------

Import a repository into GitLab and create a `master` branch
Some tools used master branch as default branch such as SonarCloud
Most Enterprise Organizations create a `master` branch for GitLab 

Settings > Repository > Default Branch > Select `master`

## To create a pipeline that uses GitLab
- Create a file in the root of the repository `.gitlab-ci.yaml`

# .gitlab-ci.yaml
- Define `Stages`
- create `jobs` which defines which `stage` it runs and use `script` to run scripts

## SonarCloud (sonarcloud.io)

SaaS platfrom that keeps source code free from:
+ Code Quality issues
+ Code Security issues
+ Define quality gates in project (such as 90% code coverage)

## Quality Gates

Used to fail our builds in case security vuln are identified in source code by security tools; Enabled to prevent source code from progressing to next step of Software Life Cycle Development

## Snyk (snyk.io)

+ Helps security issues in third-party / open source libraries (SCA)
+ Container security
+ Infra as Code security (Config issues)
+ 