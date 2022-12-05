#
# Exam AZ-400: Designing and Implementing Microsoft DevOps Solutions

Configure processes and communications (10—15%)

Configure activity traceability and flow of work

[https://docs.microsoft.com/en-us/azure/devops/report/?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/report/?view=azure-devops)

- Plan and implement a structure for the flow of work and feedback cycles
- Identify appropriate metrics related to flow of work, such as cycle times, time to recovery, and lead time
  - [https://docs.microsoft.com/en-us/azure/devops/report/dashboards/cycle-time-and-lead-time?view=azure-devops&viewFallbackFrom=vsts](https://docs.microsoft.com/en-us/azure/devops/report/dashboards/cycle-time-and-lead-time?view=azure-devops&viewFallbackFrom=vsts)

![](RackMultipart20221205-1-rh8pmn_html_17d12f77923cc267.png)

- Integrate pipelines with work item tracking tools, such as Azure DevOps and GitHub
  - [https://www.azuredevopslabs.com/labs/vstsextend/github-azurepipelines/](https://www.azuredevopslabs.com/labs/vstsextend/github-azurepipelines/)
- Implement traceability policies decided by development
- Integrate a repository with Azure Boards
  - [https://learn.microsoft.com/en-us/azure/devops/boards/queries/link-work-items-support-traceability?view=azure-devops&tabs=browser#work-items-linked-to-github-artifacts](https://learn.microsoft.com/en-us/azure/devops/boards/queries/link-work-items-support-traceability?view=azure-devops&tabs=browser#work-items-linked-to-github-artifacts)

Configure collaboration and communication

- Communicate actionable information by using custom dashboards in Azure DevOps
- Document a project by using tools, such as wikis and process diagrams
- Configure release documentation, including release notes and API documentation
- Automate creation of documentation from Git history
- Configure notifications by using webhooks

Design and implement source control (15—20%)

Design and implement a source control strategy

- Design and implement an authentication strategy
  - [https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/authenticating-to-github](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/authenticating-to-github)
  - [https://docs.microsoft.com/en-au/learn/modules/migrate-to-devops/4-explore-authorization-access-strategy](https://docs.microsoft.com/en-au/learn/modules/migrate-to-devops/4-explore-authorization-access-strategy)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/projects/connect-to-projects?toc=%2Fazure%2Fdevops%2Frepos%2Ftoc.json&bc=%2Fazure%2Fdevops%2Frepos%2Fbreadcrumb%2Ftoc.json&view=azure-devops&tabs=visual-studio-2019](https://docs.microsoft.com/en-us/azure/devops/organizations/projects/connect-to-projects?toc=%2Fazure%2Fdevops%2Frepos%2Ftoc.json&bc=%2Fazure%2Fdevops%2Frepos%2Fbreadcrumb%2Ftoc.json&view=azure-devops&tabs=visual-studio-2019)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/security/security-best-practices](https://docs.microsoft.com/en-us/azure/devops/organizations/security/security-best-practices?view=azure-devops)
- Design a strategy for managing large files, including Git LFS and git-fat
  - [https://www.git-tower.com/learn/git/faq/handling-large-files-with-lfs/](https://www.git-tower.com/learn/git/faq/handling-large-files-with-lfs/)
- Design a strategy for scaling and optimizing a Git repository, including Scalar and cross-repository sharing
- Implement workflow hooks

Plan and implement branching strategies for the source code

- Design a branch strategy, including trunk-based, feature branch, and release branch
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance](https://docs.microsoft.com/en-us/azure/devops/repos/git/git-branching-guidance?view=azure-devops)
  - [https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development](https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development)
  - [https://www.bmc.com/blogs/devops-branching-strategies/](https://www.bmc.com/blogs/devops-branching-strategies/)
- Design and implement a pull request workflow by using branch policies and branch protections
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-policies-overview](https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-policies-overview?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-policies? tabs=browser](https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-policies?view=azure-devops&tabs=browser)
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/repository-settings](https://docs.microsoft.com/en-us/azure/devops/repos/git/repository-settings?source=recommendations&view=azure-devops&tabs=browser)
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-permissions](https://docs.microsoft.com/en-us/azure/devops/repos/git/branch-permissions?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/about-pull-requests](https://docs.microsoft.com/en-us/azure/devops/repos/git/about-pull-requests?view=azure-devops)
- Implement branch merging restrictions by using branch policies and branch protections
  - [https://docs.microsoft.com/en-us/azure/devops/repos/git/merging-with-squash](https://docs.microsoft.com/en-us/azure/devops/repos/git/merging-with-squash?view=azure-devops)

Configure and manage repositories

- Integrate GitHub repositories with Azure Pipelines, one of the services in Azure DevOps
- Configure permissions in the source control repository
- Configure tags to organize the source control repository
- Recover data by using Git commands
- Purge data from source control

Design and implement build and release pipelines (40—45%)

Design and implement pipeline automation

[https://docs.microsoft.com/en-us/learn/paths/build-applications-with-azure-devops/](https://docs.microsoft.com/en-us/learn/paths/build-applications-with-azure-devops/)

- Integrate pipelines with external tools, including dependency scanning, security scanning, and code coverage

![](RackMultipart20221205-1-rh8pmn_html_32960e277f38fa48.png)

  - [https://docs.microsoft.com/en-au/learn/modules/introduction-to-secure-devops/](https://docs.microsoft.com/en-au/learn/modules/introduction-to-secure-devops/)
  - [https://docs.microsoft.com/en-au/devops/devsecops/enable-devsecops-azure-github](https://docs.microsoft.com/en-au/devops/devsecops/enable-devsecops-azure-github?view=azure-devops)
  - [https://medium.com/codex/test-coverage-code-scan-dependency-scan-and-security-scan-in-an-azure-devops-pipeline-136fa37b6b8b](https://medium.com/codex/test-coverage-code-scan-dependency-scan-and-security-scan-in-an-azure-devops-pipeline-136fa37b6b8b)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/test/publish-code-coverage-results](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/test/publish-code-coverage-results?view=azure-devops)
  - [https://www.sonarqube.org/microsoft-azure-devops-integration/](https://www.sonarqube.org/microsoft-azure-devops-integration/)
  - [https://secdevtools.azurewebsites.net](https://secdevtools.azurewebsites.net/)
  - [https://azure.microsoft.com/en-au/solutions/devsecops/#overview](https://azure.microsoft.com/en-au/solutions/devsecops/#overview)
  - [https://www.youtube.com/watch?v=ctCLx7\_sT88](https://www.youtube.com/watch?v=ctCLx7_sT88)
- Design and implement quality and release gates, including security and governance
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/?view=azure-devops)
- Design integration of automated tests into a pipeline
  - [https://docs.microsoft.com/en-us/learn/modules/run-quality-tests-build-pipeline/2-what-is-automated-testing](https://docs.microsoft.com/en-us/learn/modules/run-quality-tests-build-pipeline/2-what-is-automated-testing)

![](RackMultipart20221205-1-rh8pmn_html_4ec34fb54b9802cd.png)

  - [https://docs.microsoft.com/en-au/learn/modules/configure-provision-environments/4-configure-automated-integration-functional-test-automation](https://docs.microsoft.com/en-au/learn/modules/configure-provision-environments/4-configure-automated-integration-functional-test-automation)
  - [https://docs.microsoft.com/en-us/learn/modules/run-quality-tests-build-pipeline/](https://docs.microsoft.com/en-us/learn/modules/run-quality-tests-build-pipeline/)
- Design and implement a comprehensive testing strategy
  - [https://docs.microsoft.com/en-us/azure/devops/test/](https://docs.microsoft.com/en-us/azure/devops/test/?view=azure-devops)
- Implement orchestration of tools, such as GitHub Actions and Azure Pipelines
  - [https://docs.microsoft.com/en-au/learn/paths/az-400-implement-ci-azure-pipelines-github-actions/](https://docs.microsoft.com/en-au/learn/paths/az-400-implement-ci-azure-pipelines-github-actions/)
  - [https://docs.github.com/en/actions](https://docs.github.com/en/actions)

Design and implement a package management strategy

- Design a package management implementation that uses Azure Artifacts, GitHub Packages, NuGet, and npm
  - [https://docs.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts](https://docs.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts?view=azure-devops)
  - [https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages)
  - [https://docs.microsoft.com/en-us/nuget/what-is-nuget](https://docs.microsoft.com/en-us/nuget/what-is-nuget)
  - [https://docs.npmjs.com/about-npm](https://docs.npmjs.com/about-npm)
- Design and implement package feeds, including upstream sources
  - [https://docs.microsoft.com/en-au/learn/modules/understand-package-management/](https://docs.microsoft.com/en-au/learn/modules/understand-package-management/)
  - [https://docs.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts](https://docs.microsoft.com/en-us/azure/devops/artifacts/start-using-azure-artifacts?view=azure-devops)
- Design and implement a dependency versioning strategy for code assets and packages, including semantic versioning and date-based
  - [https://devblogs.microsoft.com/devops/versioning-nuget-packages-cd-1/](https://devblogs.microsoft.com/devops/versioning-nuget-packages-cd-1/)
  - [https://ychetankumarsarma.medium.com/build-versioning-in-azure-devops-pipelines-94b5a79f80a0](https://ychetankumarsarma.medium.com/build-versioning-in-azure-devops-pipelines-94b5a79f80a0)
- Design and implement a versioning strategy for pipeline artifacts
  - [https://cloudblogs.microsoft.com/industry-blog/en-gb/technetuk/2019/06/18/perfecting-continuous-delivery-of-nuget-packages-for-azure-artifacts/](https://cloudblogs.microsoft.com/industry-blog/en-gb/technetuk/2019/06/18/perfecting-continuous-delivery-of-nuget-packages-for-azure-artifacts/)
  - [https://www.darraghoriordan.com/2020/07/12/semantic-version-node-azure-devops/](https://www.darraghoriordan.com/2020/07/12/semantic-version-node-azure-devops/)

Design and implement pipelines

![](RackMultipart20221205-1-rh8pmn_html_6f7e04212e1ac98b.png)

- Select a deployment automation solution, including GitHub Actions and Azure Pipelines
  - [https://docs.microsoft.com/en-au/learn/paths/az-400-implement-ci-azure-pipelines-github-actions/](https://docs.microsoft.com/en-au/learn/paths/az-400-implement-ci-azure-pipelines-github-actions/)
- Design and implement an agent infrastructure, including cost, tool selection, licenses, connectivity, and maintainability
  - [https://docs.microsoft.com/en-au/learn/modules/manage-azure-pipeline-agents-pools/](https://docs.microsoft.com/en-au/learn/modules/manage-azure-pipeline-agents-pools/)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=browser#install](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=browser#install)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/pools-queues?toc=%2Fazure%2Fdevops%2Forganizations%2Ftoc.json&bc=%2Fazure%2Fdevops%2Forganizations%2Fbreadcrumb%2Ftoc.json&view=azure-devops&tabs=yaml%2Cbrowser](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/pools-queues?toc=%2Fazure%2Fdevops%2Forganizations%2Ftoc.json&bc=%2Fazure%2Fdevops%2Forganizations%2Fbreadcrumb%2Ftoc.json&view=azure-devops&tabs=yaml%2Cbrowser)

![](RackMultipart20221205-1-rh8pmn_html_8a5727580fd2e09f.png)

- Develop and implement pipeline trigger rules
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/build/triggers?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/build/triggers?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/repos/azure-repos-git?view=azure-devops&tabs=yaml#ci-triggers](https://docs.microsoft.com/en-us/azure/devops/pipelines/repos/azure-repos-git?view=azure-devops&tabs=yaml#ci-triggers)
- Develop pipelines, including classic and YAML
  - [https://docs.microsoft.com/en-au/learn/modules/integrate-azure-pipelines/](https://docs.microsoft.com/en-au/learn/modules/integrate-azure-pipelines/)
- Design and implement a strategy for job execution order, including parallelism and multi-stage
  - [https://docs.microsoft.com/en-au/learn/modules/manage-azure-pipeline-agents-pools/](https://docs.microsoft.com/en-au/learn/modules/manage-azure-pipeline-agents-pools/)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs?view=azure-devops&tabs=ms-hosted](https://docs.microsoft.com/en-us/azure/devops/pipelines/licensing/concurrent-jobs?view=azure-devops&tabs=ms-hosted)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/test/parallel-testing-any-test-runner?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/test/parallel-testing-any-test-runner?view=azure-devops)
- Develop complex pipeline scenarios, such as containerized agents and hybrid
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/docker?view=azure-devops)
- Configure and manage self-hosted agents, including virtual machine (VM) templates and containerization
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=browser#install](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/agents?view=azure-devops&tabs=browser#install)
- Create reusable pipeline elements, including YAML templates, task groups, variables, and variable groups
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/tasks?view=azure-devops&tabs=yaml](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/tasks?view=azure-devops&tabs=yaml)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/?view=azure-devops)
- Design and implement checks and approvals by using YAML environments
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/approvals?view=azure-devops&tabs=check-pass](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/approvals?view=azure-devops&tabs=check-pass)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/environments?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/environments?view=azure-devops)

Design and implement deployments

- Design a deployment strategy, including blue/green, canary, ring, progressive exposure, feature flags, and A/B testing
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops)
  - [https://docs.microsoft.com/en-au/learn/paths/az-400-implement-secure-continuous-deployment/](https://docs.microsoft.com/en-au/learn/paths/az-400-implement-secure-continuous-deployment/)
  - [https://docs.microsoft.com/en-us/azure/architecture/framework/devops/release-engineering-cd](https://docs.microsoft.com/en-us/azure/architecture/framework/devops/release-engineering-cd)
- Design a pipeline to ensure reliable order of dependency deployments
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml)
- Plan for minimizing downtime during deployments by using VIP swap, load balancer, and rolling deployments
  - [https://thegreenerman.medium.com/plan-the-deployment-environment-strategy-9b617783f6e](https://thegreenerman.medium.com/plan-the-deployment-environment-strategy-9b617783f6e)
- Design a hotfix path plan for responding to high-priority code fixes
- Implement load balancing for deployment, including Azure Traffic Manager and the Web Apps feature of Azure App Service
  - [https://azure.microsoft.com/en-in/blog/blue-green-deployments-using-azure-traffic-manager/](https://azure.microsoft.com/en-in/blog/blue-green-deployments-using-azure-traffic-manager/)
  - [https://devblogs.microsoft.com/devops/considerations-on-using-deployment-slots-in-your-devops-pipeline/](https://devblogs.microsoft.com/devops/considerations-on-using-deployment-slots-in-your-devops-pipeline/)
  - [https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#add-a-deployment-slot](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots#add-a-deployment-slot)

![](RackMultipart20221205-1-rh8pmn_html_c3bf24f8c4cf2c3.png)

- Implement feature flags by using Azure App Configuration Feature Manager
  - [https://docs.microsoft.com/en-us/azure/azure-app-configuration/overview](https://docs.microsoft.com/en-us/azure/azure-app-configuration/overview)
  - [https://docs.microsoft.com/en-us/azure/azure-app-configuration/manage-feature-flags](https://docs.microsoft.com/en-us/azure/azure-app-configuration/manage-feature-flags)
- Implement application deployment by using containers, binary, and scripts
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops)

Design and implement infrastructure as code (IaC)

[https://docs.microsoft.com/en-au/learn/paths/az-400-manage-infrastructure-as-code-using-azure/](https://docs.microsoft.com/en-au/learn/paths/az-400-manage-infrastructure-as-code-using-azure/)

_ **Configuration management** _ _refers to automated configuration management, typically in version-controlled scripts, for an application and all the environments needed to support it._

![](RackMultipart20221205-1-rh8pmn_html_2627361d3c0500b7.png)

- Recommend a configuration management technology for application infrastructure
- Implement a configuration management strategy for application infrastructure, including IaC
- Define an IaC strategy, including source control and automation of testing and deployment
- Design and implement desired state configuration for environments, including Azure Automation State Configuration, Azure Resource Manager, Bicep, and Azure Policy guest configuration
  - [https://docs.microsoft.com/en-au/azure/azure-resource-manager/management/overview](https://docs.microsoft.com/en-au/azure/azure-resource-manager/management/overview)
  - [https://docs.microsoft.com/en-us/azure/automation/automation-dsc-overview](https://docs.microsoft.com/en-us/azure/automation/automation-dsc-overview)
  - [https://docs.microsoft.com/en-au/training/modules/implement-desired-state-configuration-dsc/1-introduction](https://docs.microsoft.com/en-au/training/modules/implement-desired-state-configuration-dsc/1-introduction)

Maintain pipelines

- Monitor pipeline health, including failure rate, duration, and flaky tests
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport?view=azure-devops#test-failures-report](https://docs.microsoft.com/en-us/azure/devops/pipelines/reports/pipelinereport?view=azure-devops#test-failures-report)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/test/flaky-test-management?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/test/flaky-test-management?view=azure-devops)
- Optimize pipelines for cost, time, performance, and reliability
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/release/caching?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/caching?view=azure-devops)
- Analyze pipeline load to determine agent configuration and capacity
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/pool-consumption-report?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/pool-consumption-report?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/scale-set-agents?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/scale-set-agents?view=azure-devops)
- Design and implement a retention strategy for pipeline artifacts and dependencies
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/policies/retention?view=azure-devops&tabs=yaml](https://docs.microsoft.com/en-us/azure/devops/pipelines/policies/retention?view=azure-devops&tabs=yaml)

Develop a security and compliance plan (10—15%)

Design and implement a strategy for managing sensitive information in automation

- Implement and manage service connections
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops&tabs=yaml](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops&tabs=yaml)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/connect-to-azure?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/connect-to-azure?view=azure-devops)
- Implement and manage personal access tokens
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-pats-with-policies-for-administrators?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-pats-with-policies-for-administrators?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-personal-access-tokens-via-api?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/manage-personal-access-tokens-via-api?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/admin-revoke-user-pats?toc=%2Fazure%2Fdevops%2Forganizations%2Fsecurity%2Ftoc.json&bc=%2Fazure%2Fdevops%2Forganizations%2Fsecurity%2Fbreadcrumb%2Ftoc.json&view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/admin-revoke-user-pats?toc=%2Fazure%2Fdevops%2Forganizations%2Fsecurity%2Ftoc.json&bc=%2Fazure%2Fdevops%2Forganizations%2Fsecurity%2Fbreadcrumb%2Ftoc.json&view=azure-devops)
- Implement and manage secrets, keys, and certificates by using Azure Key Vault, GitHub secrets, and Azure Pipelines secrets
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/release/azure-key-vault?view=azure-devops&tabs=yaml](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/azure-key-vault?view=azure-devops&tabs=yaml)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/process/set-secret-variables?view=azure-devops&tabs=yaml%2Cbash](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/set-secret-variables?view=azure-devops&tabs=yaml%2Cbash)
  - [https://docs.github.com/en/actions/security-guides/encrypted-secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets)
- Design and implement a strategy for managing sensitive files during deployment
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/library/secure-files?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/library/secure-files?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts](https://docs.microsoft.com/en-us/azure/key-vault/general/basic-concepts)
- Design pipelines to prevent leakage of sensitive information
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/security/security-best-practices?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/organizations/security/security-best-practices?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/organizations/security/about-security-identity?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/organizations/security/about-security-identity?view=azure-devops)

Automate security and compliance scanning

- Automate analysis of source code by using GitHub code scanning, GitHub secrets scanning, pipeline-based scans, and SonarQube
  - [https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning)
  - [https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning)
  - [https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/security/overview?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/security/overview?view=azure-devops)
  - [https://docs.microsoft.com/en-us/azure/devops/pipelines/security/resources?view=azure-devops](https://docs.microsoft.com/en-us/azure/devops/pipelines/security/resources?view=azure-devops)
  - [https://docs.sonarqube.org/latest/analysis/azuredevops-integration/](https://docs.sonarqube.org/latest/analysis/azuredevops-integration/)
- Automate security scanning, including container scanning and OWASP ZAP
  - [https://medium.com/adessoturkey/owasp-zap-security-tests-in-azure-devops-fe891f5402a4](https://medium.com/adessoturkey/owasp-zap-security-tests-in-azure-devops-fe891f5402a4)
  - [https://medium.com/capgemini-microsoft-team/automated-pen-testing-using-owasp-zap-and-a-custom-azure-devops-extension-a1bc81b3c471](https://medium.com/capgemini-microsoft-team/automated-pen-testing-using-owasp-zap-and-a-custom-azure-devops-extension-a1bc81b3c471)
  - [https://medium.com/swlh/penetration-test-for-azure-functions-using-zap-api-scan-5a3bfc21b7e6](https://medium.com/swlh/penetration-test-for-azure-functions-using-zap-api-scan-5a3bfc21b7e6)
- Automate analysis of licensing, vulnerabilities, and versioning of open-source components by using WhiteSource and GitHub Dependency Scanning
  - [https://www.azuredevopslabs.com/labs/vstsextend/whitesource/](https://www.azuredevopslabs.com/labs/vstsextend/whitesource/)
  - [https://popovskas.com/category/azure-devops/](https://popovskas.com/category/azure-devops/)
  - [https://marketplace.visualstudio.com/items?itemName=whitesource.whiteSource-bolt-v2](https://marketplace.visualstudio.com/items?itemName=whitesource.whiteSource-bolt-v2)
  - [https://docs.github.com/en/code-security/dependabot/dependabot-alerts/configuring-dependabot-alerts](https://docs.github.com/en/code-security/dependabot/dependabot-alerts/configuring-dependabot-alerts)

Implement an instrumentation strategy (10—15%)

Configure monitoring for a DevOps environment

![](RackMultipart20221205-1-rh8pmn_html_528ec033127fca9b.png)

[https://docs.microsoft.com/en-au/training/modules/implement-tools-track-usage-flow/](https://docs.microsoft.com/en-au/training/modules/implement-tools-track-usage-flow/)

- Configure and integrate monitoring by using Azure Monitor
  - [https://docs.microsoft.com/en-us/azure/azure-monitor/overview](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)
- Configure and integrate with monitoring tools, such as Azure Monitor and Application Insights
  - [https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings?tabs=portal](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings?tabs=portal)
  - [https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview?tabs=net](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview?tabs=net)
- Manage access control to the monitoring platform
  - [https://learn.microsoft.com/en-us/azure/azure-monitor/logs/manage-access?tabs=portal](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/manage-access?tabs=portal)
- Configure alerts for pipeline events

Analyze metrics

- Inspect distributed tracing by using Application Insights
  - [https://learn.microsoft.com/en-us/azure/azure-monitor/app/distributed-tracing](https://learn.microsoft.com/en-us/azure/azure-monitor/app/distributed-tracing)
- Inspect application performance indicators
  - [https://learn.microsoft.com/en-us/azure/azure-monitor/app/tutorial-performance](https://learn.microsoft.com/en-us/azure/azure-monitor/app/tutorial-performance)
- Inspect infrastructure performance indicators, including CPU, memory, disk, and network
- Identify and monitor metrics for business value
- Analyze usage metrics by using Application Insight
- Interrogate logs using basic Kusto Query Language (KQL) queries
