## Continuous Integration & Development with Azure Data Factory

Practicing version control and setting up a CI/CD data pipeline with ADF and Azure DevOps.
Project is based on [Microsoft docs](https://docs.microsoft.com/en-us/azure/data-factory/continuous-integration-deployment) and Adam Paternostro's [guide](https://github.com/AdamPaternostro/Azure-Data-Factory-CI-CD-Source-Control)

## Highlighted Features
- Setting up a Git-repository and managing feature branches in the ADF UI. 
- Deploying feature branches to QA- and Production-environments using a Azure DevOps pipeline.
## Development Notes
- Ran into an issue while running Azure DevOps Pipeline, <span style="color:#DC2F3F">"No hosted parallelism has been purchased or granted"</span>, although the pipeline only involves sequential jobs. This seems to be caused by a recent policy change to the DevOps free tier, which now requires a request to be submitted before any jobs can be run. See [these](https://stackoverflow.com/questions/68405027/how-to-resolve-no-hosted-parallelism-has-been-purchased-or-granted-in-free-tie) [threads](https://docs.microsoft.com/en-us/answers/questions/477716/how-to-resolve-34no-hosted-parallelism-has-been-pu.html) for more info. 
