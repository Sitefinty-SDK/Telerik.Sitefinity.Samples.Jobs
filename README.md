Telerik.Sitefinity.Samples.Jobs
===============================

The Jobs sample project demonstrates how to create a jobs module that allows users to submit jobs applications.
The Jobs and HR module harnesses the built-in features of Sitefinity’s Content model. Its purpose is to manage job applications. Frontend users have the possibility to submit their job applications, while backend users are able to access a page in Sitefinity backend that provides an overview of all submitted applications.



### Requirements

* Sitefinity 6.3 license

* .NET Framework 4

* Visual Studio 2012

* Microsoft SQL Server 2008R2 or later versions


### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.


### Installation instructions: SDK Samples from GitHub



1. In Solution Explorer, navigate to _SitefinityWebApp_ -> *App_Data* -> _Sitefinity_ -> _Configuration_ and select the **DataConfig.config** file. 
2. Modify the **connectionString** value to match your server address.

The project refers to the following NuGet packages:

**Jobs** library

* Telerik.Sitefinity.Core.nupkg

* OpenAccess.Core.nupkg

* OpenAccess.CodeFirst.nupkg

* Telerik.Sitefinity.Content.nupkg

* Telerik.Web.UI.nupkg


**SitefinityWebApp** lbrary

* Telerik.Sitefinity.All.nupkg

**Telerik.Sitefinity.Samples.Common** library

* Telerik.Sitefinity.Core.nupkg

* OpenAccess.Core.nupkg

* Telerik.Sitefinity.Content.nupkg

You can find the packages in the official [Sitefinity Nuget Server](http://nuget.sitefinity.com).




### Login

To login to Sitefinity backend, use the following credentials: 

**Username:** admin

**Password:** password


### Additional resources

[Developers Guide](http://www.sitefinity.com/documentation/documentationarticles/developers-guide)

[Create a Jobs module](http://www.sitefinity.com/documentation/documentationarticles/developers-guide/how-to/how-to-create-a-jobs-module)
