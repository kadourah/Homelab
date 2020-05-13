
## Homelab Concourse Pipeline

Pipeline to setup Install PAS, PKS using Concourse 

Prerequisites:
1. Concourse 5.5.1
2. [Platform Automation](https://docs.pivotal.io/platform-automation/v4.3/index.html/)
3. S3 Storage
4. [Minio](https://min.io/)
5. I used [BUCC](https://github.com/starkandwayne/bucc)

### Steps

1. Publish to concourse fly -t bucc  set-pipeline --pipeline InstallFoundation --config InstallFoundation.yml

> Written with [StackEdit](https://stackedit.io/).