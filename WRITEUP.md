# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- _Choose the appropriate solution (VM or App Service) for deploying the app_
- _Justify your choice_
  For this project, I opted into using an App Service.
  Let's take a look why:

- Costs -
  In general, an app service would be more economical for this project. Deploying to a Virtual Machine
  would've been more costly.

- Scalability -
  This project isn't performance crazy. Both the VM and App Service solution would satisfy its needs.
  App Services have auto scalability. However, if this was expecting heavy traffic, then a VM would
  probably be a better solution.

- Availability -
  VM definitely offers better availability than an App Service as multiple VMs can be grouped together.
  An App Service also has high availability. Overall, either option would suffice for this project.

- Workflow -
  For this project, as a developer it seems more convenient for us to just focus on the application while
  Azure takes care of the infrastructure. Don't have to worry about time being spent on a VM.

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._
Given that this project is just 'course' related, no large production foreseeable events are expected.
Now, if this project was more resource heavy, and we're expecting great activity in production, then
I possibly might've changed my decision and chose to opt in for a VM. It's all a use case scenario.
