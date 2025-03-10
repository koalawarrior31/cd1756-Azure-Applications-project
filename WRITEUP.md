# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 


For this project, I chose App Service as the compute service solution because of the reasons below.
    - Application is lightweight and simple
    - Application is purely written in python and no other external applications are being used.
    - Easier option given the code and small data volume

If the application will utilize other applications, i.e. a messaging broker, I will probably prefer the VM so it can also host the broker for example. 