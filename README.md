# Azure Serverless Computing Cookbook Second Edition Java
## Introduction
When using Java with Azure Functions we don't have the portal support available with C#.  Because of this we will need to do the development in **Visual Studio Code** right from the start.  If you have followed along in the C# view presented in the mainline of the book this will be unfamiliar until Chapter 4.
## Getting Started
### Preparing your development workstation
To follow along with the recipes in this book you will need to setup a development workstation and install the following software:
- JDK (version 8 or above)
- Maven
- NodeJS (required for the package manager - npm)
- Azure Functions Core Tools (npm install -g azure-functions-core-tools)
- Visual Studio Code
- Azure Storage Explorer

You will also need to install the following extensions for Visual Studio Code:
- Java Extension Pack
- Debugger for Java
- C#
- Azure Functions

Once all the above is installed you can start your first Azure Functions as follows:
1. In Visual Studio Code, open the Azure Functions explorer
2. Create a new function by clicklign on the **Creat functions..** icon
3. Click **Browse..**
4. Create a folder to hold your function project and select it
5. When the initialisation dialog pops up click **Yes**
6. Select Java as the language for your function project
7. Enter a group ID for the maven project. I used **com.packtpub**
8. Enter an artefact Id for the maven project.  I used **packtpub-functions**
9. Enter a version for the maven project.  I used **1.0-SNAPSHOT**
10. Enter a Java package for the maven project.  I used **com.packtpub**
11. Enter a name for the function.  Based on the first Recepie in chapter 1, I used **RegisterUser**
12. Select HttpTrigger
13. Enter a Java package again.  I used **com.packtpub**
14. Enter a function name.  I used **Register User**
15. Select the **Anonymous** Authorisation Level
16. Select how you would like to open your project.  I used **Open in current window**
17.  Your function project will now initialise and open in the explorer.  All the required configuration files are automatically created.  In addition to your RegisterUser.java, a defailt called Function.java will also have been creted; you are free to delete that source file and any test source files related to it.

The following examples are complete project folders so these steps are for your information and to help you if you want to start with a fresh project and build up your own functions independently of the examples.
