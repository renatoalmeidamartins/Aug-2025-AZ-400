# Aug-2025-AZ-400

## Trainer contact details:
- [LinkedIn profile](https://www.linkedin.com/in/renatodealmeidamartins/)


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

## Day 2 links (Learning path 2 - Implement CI with Azure Pipelines and GitHub Actions)
- [Defining stages in Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/stages?view=azure-devops&tabs=yaml)
- [Documentation of all tasks available in Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/?view=azure-pipelines&viewFallbackFrom=azure-devops)
- [Details (software, hardwarde, networking) for MS hosted agents](https://learn.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=windows-images%2Cyaml)
- [Reusing parts of the pipeline as templates](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=azure-devops&pivots=templates-includes)
- [GitHub default environment variables](https://docs.github.com/en/actions/reference/workflows-and-actions/variables)
- [Using status badges](https://docs.github.com/en/actions/how-tos/monitor-workflows/add-a-status-badge)
- [Sample Dockerfile for a .Net application](https://github.com/dockersamples/dotnet-album-viewer/blob/master/docker/app/Dockerfile)
- [Full Dockerfile reference](https://docs.docker.com/reference/dockerfile/)
- [Using multi-stage builds in Dockerfiles](https://docs.docker.com/build/building/multi-stage/)
- 
