## CI/CD Azure DevOps Reference
---

### CI Flow
- Build Docker file and Push Gitlab/Docker hub with encrypted credentials
- Publish environment file as artifact for Deployment Pipeline to download

### Release Pipeline Flow Test
- Download Artifact from the build pipeline which 
  contains the variables 
- replace variable inside manifest yml file