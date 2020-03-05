# azure-singularity-agent
An agent for Azure Pipelines using a Singularity image

Build with
```
sudo singularity build azure-singularity-agent.sif Singularity
```

Run with
```
AZP_URL=https://dev.azure.com/<organization> AZP_TOKEN=<PAT token> AZP_AGENT_NAME=mydockeragent singularity run azure-singularity-agent.sif
```
