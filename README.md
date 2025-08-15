# Aug-2025-AZ-400

## Trainer contact details:
- [LinkedIn profile](https://www.linkedin.com/in/renatodealmeidamartins/)
- [Email]](mailto:renatoalmeidamartins@gmail.com)

## Evaluation form
[Link to the survey](https://www.metricsthatmatter.com/student/evaluation.asp?k=79335&i=84170)

## Course materials and labs
- [Creating a MS Learn profile](https://www.aka.ms/MyMicrosoftLearnProfile)
- [Learning path for the class](https://learn.microsoft.com/en-us/training/courses/az-400t00)
- [Description and instructions for the labs (to be done outside of the hosting environment)](https://aka.ms/az400-labs)
- [Access to hosted lab environment](https://esi.learnondemand.net/) - this requires a training key, please ask in the Teams session
## Day 1 links (Learning path 1 - Development for enterprise DevOps)
- [What is DevOps?](https://learn.microsoft.com/en-us/devops/what-is-devops), an article from MS
- [10+ deploys per day at Flicker, talk at Velocity Conference 2009, by John Allspaw and Paul Hammond](https://www.youtube.com/watch?v=LdOe18KhtT4&t=12s)
- Interesting books about DevOps:
  - [The Phoenix project](https://www.amazon.com/Phoenix-Project-bestselling-author-Unicorn/dp/1950508943/), a view of Parts Unlimited project, from the Ops side
  - [The unicorn project](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving/dp/1942788762/), someone at the same company, at the same time, wearing a developer hat
  - [The DevOps handbook](https://www.amazon.com/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1950508404/), set of musings from multiple execs of companies facing the same growth pain in the early 2000's, and how did they come to more or less the same solutions
  - [Accelerate book](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339/), the book with questionnaire leading to ["The state of devops report"](https://services.google.com/fh/files/misc/2024_final_dora_report.pdf). The link is for the 2024 edition, these are published every year.
- [There's no place like production](https://imwrightshardcode.com/2010/12/theres-no-place-like-production/)
- Poor interaction with customer, leading to...![Poor requirements gathering](https://miro.medium.com/v2/resize:fit:720/format:webp/1*SY1SmBI-eFiVK5HlVzTBUg.jpeg)
- [Strangler Fig pattern, in the Azure architecture Center](https://learn.microsoft.com/en-us/azure/architecture/patterns/strangler-fig), this is an interesting way to move from monolithic apps into microservices
- [Containerizing an application](https://learn.microsoft.com/en-us/dotnet/core/docker/build-container?tabs=windows&pivots=dotnet-9-0)
- [Agile manifesto](https://agilemanifesto.org/)
- [Measure what matters](https://www.amazon.com/Measure-What-Matters-Google-Foundation/dp/0525536221/), a book defining OKRs (objective key results)  
- [Azure DevOps Services pricing](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/), notice how some services can be purchased independently
- Customizing Windows Terminal:
  - [Scott Hanselmann's initial idea](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal)
  - [MS Docs aricle following the same pattern](https://learn.microsoft.com/en-us/windows/terminal/tutorials/custom-prompt-setup)
- [Creating an Azure DevOps organization](https://go.microsoft.com/fwlink/?LinkId=307137)
- [Landing page for Azure DevOps](https://dev.azure.com/)
- Branching strategies, or workflows:
  - [GitFlow process](https://nvie.com/posts/a-successful-git-branching-model/)
  - [GitHub flow, aka trunk-based development](https://docs.github.com/en/get-started/using-github/github-flow)
- [Git hooks](https://git-scm.com/book/ms/v2/Customizing-Git-Git-Hooks)
- [Storing large files in Git](https://github.com/git-lfs/git-lfs)
- [Partial and shallow clones in git](https://github.blog/open-source/git/get-up-to-speed-with-partial-clone-and-shallow-clone/)
- Scalar, useful for fine-tuning how git works on large repos, [the tool](https://git-scm.com/docs/scalar) and [the story behind it](https://github.blog/open-source/git/the-story-of-scalar/)
- [GitHub CLI](https://cli.github.com/manual/gh)
- [git log](https://git-scm.com/docs/git-log), shows commit logs, targeting specific versions if needed
- [git tagging](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
- Documenting APIs:
  - [Doc on MS to use DotNet directly for that](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/openapi/overview?view=aspnetcore-9.0)
  - [Swagger doc illustrating a few ways to do it](https://swagger.io/resources/articles/documenting-apis-with-swagger/)
- Repo cleaning tools:
  - [BFG Repo Cleaner](https://rtyley.github.io/bfg-repo-cleaner/)
  - [git filter-repo tool](https://github.com/newren/git-filter-repo)
- [Clean code, book with ideas on how to create beautiful code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882/)

## Day 2 links ("Learning path 2 - Implement CI with Azure Pipelines and GitHub Actions" and "Learning path 3 - Design and implement a release strategy")
- [Defining stages in Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml)
- [Documentation of all tasks available in Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/?view=azure-pipelines&viewFallbackFrom=azure-devops)
- [Details (software, hardwarde, networking) for MS hosted agents](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=windows-images%2Cyaml)
- [Reusing parts of the pipeline as templates](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops&pivots=templates-includes)
- [GitHub default environment variables](https://docs.github.com/en/actions/reference/workflows-and-actions/variables)
- [Using status badges](https://docs.github.com/en/actions/how-tos/monitor-workflows/add-a-status-badge)
- [Sample Dockerfile for a .Net application](https://github.com/dockersamples/dotnet-album-viewer/blob/master/docker/app/Dockerfile)
- [Full Dockerfile reference](https://docs.docker.com/reference/dockerfile/)
- [Using multi-stage builds in Dockerfiles](https://docs.docker.com/build/building/multi-stage/)
- Interesting info about GitOps:
  - [GitLab defining it](https://about.gitlab.com/topics/gitops/)
  - [Weaveworks defining it, they have a very mature solution, endorsed by CNCF](https://docs.gitops.weaveworks.org/docs/intro-weave-gitops/)
- [Types of tests avaiable through application insights on Azure](https://learn.microsoft.com/en-us/azure/azure-monitor/app/availability?tabs=standard) - notice that Url ping and multi-step web tests are deprecated
- [Azure Load testing (currently App Test) documentation](https://learn.microsoft.com/en-us/azure/app-testing/load-testing/overview-what-is-azure-load-testing)
- [Task groups](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/task-groups?view=azure-devops), notice that they are only available on classic pipeliens. Equivalent to this on yaml pipelines are the templates.
- [Release strategies, each exposing different lifecycle hooks](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops)
- [Release strategies in the Azure Architecture center](https://learn.microsoft.com/en-us/azure/architecture/microservices/ci-cd)

## Day 3 links ("Learning path 4 - Implement a secure continuous deployment using Azure Pipelines" and "Learning Path 5 - Manage infrastructure as code using Azure and DSC")
- [Feature flags](https://martinfowler.com/articles/feature-toggles.html)
- [Using Azure App Configuration for feature flags](https://learn.microsoft.com/en-us/azure/azure-app-configuration/manage-feature-flags?tabs=azure-portal)
- Using Traffic manager to help with canary or blue-green deployments:
  - [Traffic manager routing methods](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods)
  - [Types of endpoints supported by traffic manager](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-endpoint-types)
- [Seeting up SSO in a GitHub environment](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-single-sign-on/about-authentication-with-single-sign-on)
- [GitHub roles available in organizations](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization)
- [Default groups in Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/organizations/security/about-permissions?view=azure-devops&tabs=preview-page)
- [Good practices for using Azure App Configuration](https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-best-practices?tabs=dotnet)
- [GitOps and its relation to inner and outer loops](https://learn.microsoft.com/en-us/azure/azure-arc/kubernetes/conceptual-inner-loop-gitops)
- [ARM template syntax](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/syntax)
- [ARM template functions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions)
- [Secret references in ARM templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/key-vault-parameter?tabs=azure-cli)
- [Bicep syntax](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/file)
- [Example lab for using Terraform in Azure DevOps](https://github.com/Azure-Samples/azure-devops-terraform-oidc-ci-cd#demo--lab)
- [Terraform labs on Azure, from zero to hero](https://azure-samples.github.io/terraform-fundamentals-labs/)
- [Azure automation GitHub organization](https://github.com/azureautomation), has a lot of sample runbooks
- [Powershell workflows](learn.microsoft.com/en-us/powershell/module/psworkflow/about/about_workflows?view=powershell-5.1&viewFallbackFrom=powershell-7.6)
- [Parallel processing in PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/learn/deep-dives/write-progress-across-multiple-threads?view=powershell-7.5), be careful with race conditions. You will need a mutli-thread aware class to write something out.
[Using Azzure Policy to avoid configuration drift](https://learn.microsoft.com/en-us/azure/governance/policy/how-to/remediate-resources?tabs=azure-portal)
- [Power shell desired state configuration](https://learn.microsoft.com/en-us/powershell/dsc/overview?view=dsc-3.0)
- [Dependencies when using bicep files](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/resource-dependencies)
  
## Day 4 links ("Learning path 6 - Implement security and validate code bases for compliance", "Learning Path 7 - Design and implement a dependency management strategy" and "Learning path 8 - ")
- [Exploits of a mom](https://xkcd.com/327/), Little bobby tables doing SQL injection since he was born
- [Log4j exploit through log4shell](https://en.wikipedia.org/wiki/Log4Shell)
- [Threat dragon](https://owasp.org/www-project-threat-dragon/), tool from OWASP for threat modeling
- [Microsoft threat modeling tool](https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool), latest release is quite old, from 2022
- [CodeQL](https://codeql.github.com/docs/codeql-overview/)
- [CNCF landscape, showing all the projects, and their maturity, from CNCF](https://landscape.cncf.io/)
- [GitHUb dependabot](https://github.com/dependabot/dependabot-core)
- Mend, Checkmarx, Veracode, Black Duck by Synopsis, SonarQube among others are nice tools for SCA, code scanning and other aspects of DevSecOps
- Container scanning shouldn't be ignored. Some tools are:
  - [Trivy](https://github.com/aquasecurity/trivy)
  - [Clair](https://github.com/quay/clair)
  - [Defender for containers](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-containers-introduction)
- [Azure policy language](https://learn.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure-basics)
- [GitHub Advanced security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security)
- [Permissions on feeds hosted by Azure DevOps Artifacts](https://learn.microsoft.com/en-us/azure/devops/artifacts/feeds/feed-permissions?view=azure-devops&tabs=nuget%2Cnugetserver22%2Cnugetserver)
- [Semantic versioning](https://semver.org/)
- [KQL Syntax](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference)
- [Kusto main functions](https://learn.microsoft.com/en-us/kusto/query/tutorials/learn-common-operators?view=microsoft-fabric)
- [Native integrations with ITSM systems - available for ServiceNow and BMC](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/itsmc-overview)
- [Smart detection on application insights](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-diagnostics)
- [One approach to run a blameless post-mortem](https://www.atlassian.com/incident-management/postmortem/blameless)
- [Postmortem culture from Google SRE book](https://sre.google/sre-book/postmortem-culture/)

## Sample prompt to have an LLM helping with exam preparation

I am preparing for the AZ-400 exam. The content of the exam can be seen here https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400#skills-measured-as-of-july-26-2024 . You are my assistant for the preparation. Come up with one question at a time, multiple choice, that will test me on the content linked above. Questions should be similar in structure to the structure below:<br><br>

Question: You manage the deployment of an Azure App Service web app named App1 to multiple Azure regions.  You need to identify which Azure service enables you to validate the availability of App1 from multiple locations around the world. What should you identify?<br><br>

Select only one answer.<br>
A - Application Insights<br>
B - Azure Advisor<br>
C - Azure App Configuration<br>
D - Azure Service Health<br>

After I answer each question, tell me why it is wrong or right, and come up with a new question.
```
