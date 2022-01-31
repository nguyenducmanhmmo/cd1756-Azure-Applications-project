# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

### Solution
- VM
+ More expensive
+ High availability, scalability, and redundancy by grouping Multiple VMs with 2 options
Virtual Machine Scale Sets and Load Balancers
+ More time consuming workflow, have to remote to server, build, publish code to webserver
- App Service
+ paying for the service plan
+ High availability, auto-scaling(Vertical or Horizontal scaling)
+ fast workflow, deploy by using only one command

- For this course, app service is chossen
- I chose app service because I don't need control the underlying OS or install software on the server, python is supported for app service and fast deploy

### Change Decision
- I would choose to VM if this app use language is not supported, and if I know this app'g gonna
go big, not just lightweight wepbapp.
