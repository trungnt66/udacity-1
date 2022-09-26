# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

- App Service solution had easier workflow.
  + App Service has easy deployment workflow, just connect to github repository and setup, without complex configuration like VM.
- App service is cheaper when compare with VM.
  + With App Service for this project I just use 1gb linux plan with totally free cost.
- I choose App Service solution instead of VM because:
  + Better cost.
  + Deployment time is fast.
  + App is simple, I do not need to use VM.
  + Azure take care alot for security control.
  + With App Service Azure take care alot of availability, with VM I need to has more responsbility for it.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

- The application needs more control over current requirements. Example we need an application need higher scalabiltity.
- When I need to support more programing languages, example when Azure App Service not support that languages.