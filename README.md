# KInspector
[![Build status](https://ci.appveyor.com/api/projects/status/udykjx510v83w9y6?svg=true)](https://ci.appveyor.com/project/kentico/kinspector)

KInspector is an application for analyzing **Kentico**. It was developed by the consulting department to automatize common tasks.

The application contains three types of modules. The **setup** modules that somehow makes easier setup of the CMS instance (e.g.: disable SMTP servers). The **analysis** modules checks for the performance and health and the **security** modules are checking for potential security issues like XSS or SQL injection throughout the system.

The KInspector is written as an independent .NET application from Kentico and could analyze **any version** of it. It supports work with the database, file system as well as with the API.


## Get the tool

It's super easy. Download the [latest release](https://github.com/Kentico/KInspector/releases/latest) zip package, unpack it and run the ```Start.cmd```. It automatically opens a new browser window with the [target setup](http://i.imgur.com/4n5s56z.png) page. 
> Make sure that you provide all the fields with the correct value. Some of the modules works with the database and some of them with a code. If you don't fill the values correctly, it can throw an error.

On a [main menu](http://i.imgur.com/H7zBQOZ.png) page, select ```Analysis``` category and run the modules. You will see a page similar to this one

[![Module results](http://i.imgur.com/UUdTlNL.png)](http://i.imgur.com/Vti1Fo7.png)

## Contributing
Want improve the KInspector? Great! Read the [contributing guidelines](https://github.com/Kentico/KInspector/blob/master/CONTRIBUTING.md) and then [write your first module](https://github.com/Kentico/KInspector/wiki/Writing-a-custom-module) or improve the existing one.

If anything feels wrong or incomplete, please let us know. Create a new [issue](https://github.com/Kentico/KInspector/issues/new) or submit a [pull request](https://help.github.com/articles/using-pull-requests/).
