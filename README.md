related-data-migration
======================

[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.RelatedDataMigration.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.RelatedDataMigration.CI/)


With the release of Sitefinity 7.0, new [Related Data/Media field](http://www.sitefinity.com/documentation/documentationarticles/related-data-field) was introduced. Using it you can create one to one or one to many relations between Sitefinity items including: dynamic content, News, Events, Blog posts, Pages. Sitefinity makes it easy to display all related items on the frontend.
If you, however, have already [created Field control with selector for dynamic items](http://www.sitefinity.com/documentation/documentationarticles/creating-field-control-with-selector-for-dynamic-items) you may come across the need to migrate your content to the new fields. In order to do that, we have prepared a simple code that will help you go through the migration process.


### Requirements

* Sitefinity license

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
3. Build the solution.


### Login

To login to Sitefinity backend, use the following credentials: 

**Username:** admin

**Password:** password

### Additional resources

[Migrate related data with the Migration Assistant](http://www.sitefinity.com/documentation/documentationarticles/related-data-migration)

