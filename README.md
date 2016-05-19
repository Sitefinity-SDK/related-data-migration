related-data-migration
======================

[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.RelatedDataMigration.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.RelatedDataMigration.CI/)


As of Sitefinity CMS version 7.0, you can use the Related data and Related media fields to create one-to-one or one-to-many relations between Sitefinity CMS content types including: dynamic content, News, Events, Blogs, Blog posts, Pages, and others. Sitefinity CMS makes it easy to display all related items on the frontend. For more information, see [Content relations](http://www.sitefinity.com/documentation/documentationarticles/related-data-field).

In case you have previously used Guid, Guid array, or Media field, you can now migrate their content to use the new Related data and Related media custom fields. To do this, you use the Migration Assistant.
NOTE: You can also register external scripts that you used with Guid or Guid array fields with a Thunder selector.

### Requirements

* Sitefinity CMS license
* Sitefinity CMS version 7.0.5107 and newer
* .NET Framework 4
* Visual Studio 2012
* Microsoft SQL Server 2008R2 or later versions

### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.

### Nuget package restoration
The solution in this repository relies on NuGet packages with automatic package restore while the build procedure takes place.   
For a full list of the referenced packages and their versions see the [packages.config](https://github.com/Sitefinity-SDK/related-data-migration/blob/master/SitefinityWebApp/packages.config) file.    
For a history and additional information related to package versions on different releases of this repository, see the [Releases page](https://github.com/Sitefinity-SDK/related-data-migration/releases).    


### Installation instructions: SDK Samples from GitHub


1. In Solution Explorer, navigate to _SitefinityWebApp_ -> *App_Data* -> _Sitefinity_ -> _Configuration_ and select the **DataConfig.config** file. 
2. Modify the **connectionString** value to match your server address.
3. Build the solution.


### Login

To login into the Sitefinity CMS backend, use the following credentials: 

**Username:** admin

**Password:** password

### Additional resources

[Migrate related data with the Migration Assistant](http://www.sitefinity.com/documentation/documentationarticles/related-data-migration)

