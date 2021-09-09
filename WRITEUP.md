# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

### Choosing a VM for the CMS app

Using a VM on The Cloud would signify lots of savings compared to buying a server to be set up on-premises, but a server for a simple app that is it just taking form could probably be seen as wasteful in terms of costs. In terms of workflow, using a VM would entail that developers would spend quite some time in the setup, since it is a server that needs to be managed, this also means that when scaling altough not representing a problem per se, it would mean more time consumed in the setup or changes. Referring to availability, if there is enough budget, it would be no problem. Summing up, choosing a VM would entail more costs in both time and resources, but with the benefit of having a more solid and planned infrastructure that would be recommended for later stages.

### Choosing an App Service for the CMS app

Usin App Service would signify even more savings, in both time and resources, since this service is specifically directed at developers that only want to focus on the application while the infrastructure is being taken care of by the Cloud provider: Azure. There are possibilities for scalability that would help to further experiment in a more advanced startup stages, but once the application needs to be managed more effectively, it could be a good move towards Kubernetes. In terms of availability, there are different options that adjust to different budgets.


### My CHOICE

My decision is based on the fact that my application is still in the very early stages and there is no use of spending a lot of money of services that would consume my developer-role available time. We could inspect carefully all the details about availability and make a decision on which option best fit our needs. Scalability would be a problem that we do not need to focus on at the moment because we are experimenting and pivoting with the end users.


### The future

Of course, once the experiments have a firm ground where we are more confident that we are on the right path, we would start to make assessments on which Cloud service best fit our needs. I would go for microservices that would allow to build small teams of developers that would take care of their own needs and based on that we can change from App Services to a more suitable service.  
