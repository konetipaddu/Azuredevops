---
pool:
  name: 'Azure Pipelines'
  VmImage: 'ubuntu-22.04'
trigger:
  - develop
steps:
  - task: DotNetCoreCLI@2
    displayName: Restore
    inputs: 
      command: restore















