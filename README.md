# Sample code for MS de:code 2017 Japan

## Multi Region Deployment
ARM/

* Edit ARM/parameters.sample.json and rename it to parameters.json
* Edit ARM/deploy.sample.ps1 if you need such as parameters and rename it to deploy.ps1
* Run ARM/deploy.ps1

## ASP.NET Core Sample app
SREDemo/

* Approximately equal to sample ASP.NET Core app generated from VS2017
* Deploy it to Azure after ARM deployment
* Need to migrate DB (Entity Framework)