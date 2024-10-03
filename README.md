# GitHub Actions

[![GitHub stars](https://img.shields.io/github/stars/austinsonger/GitHubActions?logo=github)](https://github.com/austinsonger/GitHubActions/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/austinsonger/GitHubActions?logo=github)](https://github.com/austinsonger/GitHubActions/network)
[![Lines of Code](https://img.shields.io/badge/lines%20of%20code-6.5k-lightgrey?logo=codecademy)](https://github.com/austinsonger/GitHubActions)
[![License](https://img.shields.io/github/license/austinsonger/GitHubActions)](https://github.com/austinsonger/GitHubActions/blob/master/LICENSE)
[![My LinkedIn](https://img.shields.io/badge/LinkedIn%20Profile-austinsonger-blue?logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIGZpbGw9IiNmZmZmZmYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+TGlua2VkSW48L3RpdGxlPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPgo=)](https://www.linkedin.com/in/austinsonger/)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/austinsonger/GitHubActions?logo=github)](https://github.com/austinsonger/GitHubActions/commits/master)

[![CI Builds Overview](https://img.shields.io/badge/CI%20Builds-Overview%20Page-blue?logo=circleci)](https://austinsonger.github.io/CI-CD/)
[![YAML](https://github.com/austinsonger/GitHubActions/actions/workflows/yaml.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/yaml.yaml)
[![Validation](https://github.com/austinsonger/GitHubActions/actions/workflows/validate.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/validate.yaml)
[![Grype](https://github.com/austinsonger/GitHubActions/actions/workflows/grype.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/grype.yaml)
[![Kics](https://github.com/austinsonger/GitHubActions/actions/workflows/kics.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/kics.yaml)
[![Semgrep](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep.yaml)
[![Semgrep Cloud](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep-cloud.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep-cloud.yaml)
[![URL Links](https://github.com/austinsonger/GitHubActions/actions/workflows/url_links.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/url_links.yaml)
[![Trivy](https://github.com/austinsonger/GitHubActions/actions/workflows/trivy.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/trivy.yaml)

[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-2088FF?logo=github)](https://github.com/austinsonger/GitHubActions)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-FCA121?logo=gitlab)](https://gitlab.com/austinsonger/GitHubActions)
[![Repo on Azure DevOps](https://img.shields.io/badge/repo-Azure%20DevOps-0078D7?logo=azure%20devops)](https://dev.azure.com/austinsonger/GitHub/_git/GitHubActions)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-0052CC?logo=bitbucket)](https://bitbucket.org/austinsonger/GitHubActions)

GitHub Actions master template & GitHub Actions Reusable Workflows library.

- [main.yaml](https://github.com/austinsonger/GitHubActions/blob/master/main.yaml) - GitHub Actions master workflow template
- [.github/workflows/](https://github.com/austinsonger/GitHubActions/tree/master/.github/workflows) - GitHub Actions Reusable Workflows Library

See [Documentation](https://docs.github.com/en/actions/using-workflows/reusing-workflows#calling-a-reusable-workflow) for how to call these workflows directly from your own GitHub Actions workflow.

Fork this repo to have full control over all updates via Pull Requests. Create environment branches to stage updates across dev/staging/production.

Forked from [austinsonger/Templates](https://github.com/austinsonger/Templates), for which this is now a submodule.

To see GitHub Contexts available, including undocumented fields, see [austinsonger/GitHubActions-Contexts](https://github.com/austinsonger/GitHubActions-Contexts).

## Examples

In your GitHub repo, import these workflows by adding small yaml files to the `.github/workflows/` directory.

## Scan for Secrets and Security issues

[![Semgrep](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep.yaml)
Alerts appear under the GitHub repo's Security tab -> Code scanning alerts.

[![Semgrep Cloud](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep-cloud.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/semgrep-cloud.yaml) Alerts appear in the <https://semgrep.dev> dashboard

Create `.github/workflows/semgrep.yaml` for local repo alerts:

```yaml
on: [push]
jobs:
  semgrep:
    uses: austinsonger/GitHubActions/.github/workflows/semgrep.yaml@master
```

or `.github/workflows/semgrep-cloud.yaml` for <https://semgrep.dev> alerts:

```yaml
on: [push]
jobs:
  semgrep:
    uses: austinsonger/GitHubActions/.github/workflows/semgrep-cloud.yaml@master
    secrets:
      SEMGREP_APP_TOKEN: ${{ secrets.SEMGREP_APP_TOKEN }}
```

## Analyze your Terraform code security & best practices

[![tfsec](https://github.com/austinsonger/Terraform/actions/workflows/tfsec.yaml/badge.svg)](https://github.com/austinsonger/Terraform/actions/workflows/tfsec.yaml)
Alerts appear under Security -> Code scanning alerts.

Create `.github/workflows/tfsec.yaml`:

```yaml
on: [push]
jobs:
  tfsec:
    uses: austinsonger/GitHubActions/.github/workflows/tfsec.yaml@master
```

## Terraform Plan & Apply

Plans - updates Pull Requests with the results of validation, format check and full Change Plan outputs

Apply - applies when merged to default branch, eg. `master` or `main`

```yaml
on: [push, pull_request]
jobs:
  terraform:
    uses: austinsonger/GitHubActions/.github/workflows/terraform.yaml@master
    with:
      dir: path/to/terraform/code
    secrets:
      ...
```

For more sophisticated examples including approvals, secrets, branch and path selection etc. see my [Terraform repo](https://github.com/austinsonger/Terraform)'s templates for [terraform-plan.yaml](https://github.com/austinsonger/Terraform/blob/master/.github/workflows/terraform-plan.yaml.template) and [terraform-apply.yaml](https://github.com/austinsonger/Terraform/blob/master/.github/workflows/terraform-apply.yaml.template)

## Docker Build and push to DockerHub

[![Docker Build DevOps Bash Tools (Ubuntu)](https://github.com/austinsonger/Dockerfiles/actions/workflows/docker_build_devops_bash_tools_ubuntu.yaml/badge.svg)](https://github.com/austinsonger/Dockerfiles/actions/workflows/docker_build_devops_bash_tools_ubuntu.yaml)

Create `.github/workflows/dockerhub_build.yaml`:

```yaml
on: [push]
jobs:
  docker_build:
    uses: austinsonger/GitHubActions/.github/workflows/dockerhub_build.yaml@master
    with:
      repo: user/repo  # your DockerHub user/repo
      tags: latest v1.1
    secrets:
      DOCKERHUB_USER: ${{ secrets.DOCKERHUB_USER }}
      DOCKERHUB_TOKEN: ${{ secrets.DOCKERHUB_TOKEN }}
```

## Docker Build and push to AWS ECR

Create `.github/workflows/docker_build_aws_ecr.yaml`:

```yaml
on: [push]
jobs:
  docker_build:
    uses: austinsonger/GitHubActions/.github/workflows/docker_build_aws_ecr.yaml@master
    with:
      repo: MY_ECR_REPO
    secrets:
      AWS_ACCESS_KEY_ID: ${{ secrets.AWS_ACCESS_KEY_ID }}
      AWS_SECRET_ACCESS_KEY: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
      AWS_DEFAULT_REGION: ${{ secrets.AWS_DEFAULT_REGION }}
```

Creates several useful tags, supports multi-stage build caching, see [README](https://github.com/austinsonger/GitHubActions/blob/master/.github/workflows/README.md) for details.

## Check for Broken URL Links

[![URL Links](https://github.com/austinsonger/GitHubActions/actions/workflows/url_links.yaml/badge.svg)](https://github.com/austinsonger/GitHubActions/actions/workflows/url_links.yaml)

Create `.github/workflows/url_links.yaml`:

```yaml
on: [push]
jobs:
  url_links:
    uses: austinsonger/GitHubActions/.github/workflows/url_links.yaml@master
```

See [README](https://github.com/austinsonger/GitHubActions/blob/master/.github/workflows/README.md) for details on ignoring inaccessible / partially constructed links or those containing variables

## Auto-Merge Production hotfixes back to Staging

Merges via a Pull Request for full auditing.

Create `.github/workflows/merge_production_to_staging.yaml`:

```yaml
on: [push]
jobs:
  merge:
    if: github.ref_name == 'production'
    uses: austinsonger/GitHubActions/.github/workflows/merge-branch.yaml@master
    with:
      head: production  # from
      base: staging     # to
```

## Mirror Repos to GitLab for DR Backups

Mirrors all/given GitHub repos to GitLab - including all branches and tags, and GitHub repo description

```yaml
on:
  schedule:
    # mirror to GitLab hourly
    - cron: '0 0 * * *'

jobs:
  gitlab_mirror:
    uses: austinsonger/GitHubActions/.github/workflows/gitlab-mirror.yaml@master
    with:
      #organization: my-org    # optional: mirror your company's repos instead of your personal repos
      #repos: repo1 repo2 ...  # list of repos to mirror, space separated, rather than all repos
    secrets:
      GH_TOKEN: ${{ secrets.GH_TOKEN }}
      GITLAB_TOKEN: ${{ secrets.GITLAB_TOKEN }}
```

## AWS CodeArtifact - Publish a Python Package

```yaml
on:
  tags:
    - v*

jobs:
  aws_codeartifact_python_publish:
    uses: austinsonger/GitHubActions/.github/workflows/codeartifact_python_publish.yaml@master
    with:
      domain: mycompany     # your AWS CodeArtifact service domain name
      repo: mycompany-core  # your CodeArtifact repo name
      #command: make publish_package  # default. Can be any command using CODEARTIFACT_AUTH_TOKEN and CODEARTIFACT_REPO_URL
    secrets:
      AWS_ACCESS_KEY_ID: ${{ secrets.AWS_ACCESS_KEY_ID }}
      AWS_SECRET_ACCESS_KEY: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
      AWS_DEFAULT_REGION: ${{ secrets.AWS_DEFAULT_REGION }}
```

## Production

### Option 1 - Hashref

Import the reusable workflows from this repo as shown above, replacing `@master` with `@<hashref>` to fix to an immutable version (tags are not immutable). This is [GitHub Actions Security Best Practice](https://docs.github.com/en/actions/security-guides/security-hardening-for-GitHubActions#using-third-party-actions).

### Option 2 - Public Fork (fully automated)

Fork this repo for more control and visibility over all updates.

Enable the [fork-sync](https://github.com/austinsonger/GitHubActions/blob/master/.github/workflows/fork-sync.yaml) github actions workflow in your fork to keep the master branch sync'd every few hours.

You can then create tags or environment branches in your forked repo to stage updates across dev/staging/production.

If using environment branches enable the [fork-update-pr](https://github.com/austinsonger/GitHubActions/blob/master/.github/workflows/fork-update-pr.yaml) github actions workflow to automatically raise GitHub Pull Requests from master to your environment branches to audit, authorize & control updates.

### Option 3 - Private Copy (manual)

Copy `.github/workflows` to a private repo. Not recommended as it's the most manual legacy approach.

You will be responsible for committing and reconciling any divergences in your local copies.

### Stargazers over time

[![Stargazers over time](https://starchart.cc/austinsonger/GitHubActions.svg)](https://starchart.cc/austinsonger/GitHubActions)

## More Core Repos

<!-- OTHER_REPOS_START -->

### Knowledge

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Knowledge-Base&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Knowledge-Base)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Diagrams-as-Code&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Diagrams-as-Code)

<!--

Not support on GitHub Markdown:

<iframe src="https://raw.githubusercontent.com/austinsonger/austinsonger/main/knowledge.md" width="100%" height="500px"></iframe>

Does nothing:

<embed src="https://raw.githubusercontent.com/austinsonger/austinsonger/main/knowledge.md" width="100%" height="500px" />

-->

### DevOps Code

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=DevOps-Bash-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/DevOps-Bash-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=DevOps-Python-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/DevOps-Python-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=DevOps-Perl-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/DevOps-Perl-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=DevOps-Golang-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/DevOps-Golang-tools)

<!--
[![Gist Card](https://github-readme-stats.vercel.app/api/gist?id=f8f551332440f1ca8897ff010e363e03)](https://gist.github.com/austinsonger/f8f551332440f1ca8897ff010e363e03)
-->

### Containerization

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Kubernetes-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Kubernetes-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Dockerfiles&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Dockerfiles)

### CI/CD

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=GitHubActions&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/GitHubActions)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Jenkins&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Jenkins)

### DBA - SQL

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=SQL-scripts&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/SQL-scripts)

### DevOps Reloaded

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Nagios-Plugins&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Nagios-Plugins)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=HAProxy-configs&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/HAProxy-configs)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Terraform&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Terraform)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Packer-templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Packer-templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Nagios-Plugin-Kafka&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Nagios-Plugin-Kafka)

### Templates

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Templates&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Templates)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Template-repo&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Template-repo)

### Misc

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Spotify-tools&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Spotify-tools)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=austinsonger&repo=Spotify-playlists&theme=ambient_gradient&description_lines_count=3)](https://github.com/austinsonger/Spotify-playlists)

The rest of my original source repos are
[here](https://github.com/austinsonger?tab=repositories&q=&type=source&language=&sort=stargazers).

Pre-built Docker images are available on my [DockerHub](https://hub.docker.com/u/austinsonger/).

<!-- 1x1 pixel counter to record hits -->
![](https://hit.yhype.me/github/profile?user_id=2211051)

<!-- OTHER_REPOS_END -->
