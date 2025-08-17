# Simple Node CI Demo

Minimal Express app with Jest tests and an Azure DevOps pipeline.

## Run locally
```bash
npm ci
npm test
npm start
```

App runs at http://localhost:3000 and returns "Hello, world!" on `/`.

## Azure DevOps
The pipeline YAML is in `azure-devops-pipeline.yml`. It installs dependencies,
runs tests, publishes JUnit results to the Tests tab, and uploads a tar.gz artifact.
# CD-Pipeline
