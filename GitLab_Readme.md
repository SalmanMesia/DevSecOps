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
- 