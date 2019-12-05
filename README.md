# AutomationPractice1
Project Name : PhaksAutomation

Page Object Model automation testing framework in C# using SpecFlow, Selenium and JavaScript

The framework is designed using the most popular IDE for C# , Visual Studio 2017 version 15.9.16.
The following Tools are required to be installed on your machine.

The framework Structure 
The POM framework is made up of the following folders:
 

1.	Features Folder. This folder contains SpecFlow feature files. 
2.	Pages Folder. This folder contains class files. These files will have the functionality of the pages we are testing. 
3.	Steps Folder. This folder contains the SpecFlow step definition files. 
4.	Utils Folder.  This folder contains a series of subfolders. 
- Drivers subfolder - Here we have files that control the browsers. 
- Extensions subfolder - contains class files with extension methods.
 -Helpers subfolder contains  support methods for the page classes. 
- Hooks subfolder contains files that hook SpecFlow with the rest of the code. 
- Selenium subfolder will have some configuration files

The following Tools are required to be installed on your machine.

1.	Extensions and Updates

-navigate to the Tools menu and select Extensions and Updates. In the Extensions and Updates window click on the online section. Then search for ,and install the following extensions.
a.  SpecFlow. The window is updated automatically and we see the results. Click the Download button.
b.  NUnit.  
c.  Nunit 3 Test Adapter.
d.  Productivity Power tools .this extentionis optional.

After installing the extensions ,Restart Visual Studio and follow the installation wizard.
 
2.	Nuget Packages

From the Solution Explorer right –click on References and select the Add Nuget packages option.Search and install the following packages:
a.  NUnit. NUnit is an evolving, open source framework designed for writing and running tests in Microsoft .NET programming languages. 
b.  ChromeWebDriver. This will be the main WebDriver that we will use in our tests. We also want to use a second WebDriver.
c.  Selenium Webdriver . this is the main tool that allows us to do automated tests In this tutorial we are going to use Selenium Webdriver in C#. Selenium WebDriver supports many programming languages.
d.  SpecFlow to automatically define, manage, and execute acceptance tests that are readable by people. We search for SpecFlow and install the package. 
e.  SpecFlow assist dynamic  helps us to simplify the SpecFlow tables. 
f.  Extent Reports.
After installation of the NuGet packages, a configuration file is created called packages.config. It is an XML file. In the file we can see the names and versions of the installed packages and their dependencies.
 
The framework Structure 
The POM framework is made up of the following folders:
 

1.	Features Folder. This folder contains SpecFlow feature files. 
2.	Pages Folder. This folder contains class files. These files will have the functionality of the pages we are testing. 
3.	Steps Folder. This folder contains the SpecFlow step definition files. 
4.	Utils Folder.  This folder contains a series of subfolders. 
- Drivers subfolder - Here we have files that control the browsers. 
- Extensions subfolder - contains class files with extension methods.
 -Helpers subfolder contains  support methods for the page classes. 
- Hooks subfolder contains files that hook SpecFlow with the rest of the code. 
- Selenium subfolder will have some configuration files



- 

