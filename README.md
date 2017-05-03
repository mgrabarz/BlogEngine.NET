## BlogEngine.NET Source Code
This repository provides forked source code for BlogEngine.NET project (https://blogengine.codeplex.com)

Purpose of this repository is to demonstrate ARM templates, and use them to deploy BlogEngine to your Azure subscription with just one click - ok, you still need to provide names for your infrastructure.
Template contains scalable BlogEngine deployment (on Azure WebApps), with dedicated Azure SQL instance. It also contains Azure Application Insights integration, that collects/alerts additional metrics like CPU usage or HTTP queue length.

## Dev Environment (if needed)
  * Visual Studio 2017 
  * ASP.NET 4.5
  * Azure SDK 2.9.6+

## Get started

Use buttons below to deploy/visualize preconfigured for Azure version of BlogEngine.NET.
<br />
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmgrabarz%2FBlogEngine.NET%2Fmaster%2FBlogEngine%2FBlogEngine.ArmDeployment%2FWebSiteSQLDatabase.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmgrabarz%2FBlogEngine.NET%2Fmaster%2FBlogEngine%2FBlogEngine.ArmDeployment%2FWebSiteSQLDatabase.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
