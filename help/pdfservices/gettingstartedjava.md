---
title: Getting Started with Adobe PDF Services API and Java
description: Developers can get started in just a few minutes with the ready to run sample files provided for accessing all the available web services
feature: PDF Services API
role: Developer
level: Beginner
type: Tutorial
jira: KT-6676
thumbnail: KT-6676.jpg
exl-id: 4a8f2119-c464-496b-bdc8-35dd387bef25
---
# Getting started with Adobe PDF Services API and Java

![Create PDF Hero Image](assets/GettingStartedJava_hero.jpg)

Developers can get started in just a few minutes with the ready to run sample files provided for accessing all the available web services. This tutorial walks you through all the steps to start running the samples using the PDF Services Java SDK:

## Step 1: Obtaining credentials and downloading sample files

The first step is to obtain a credential (API Key) to unlock use. [Sign up for the free trial here](https://www.adobe.io/apis/documentcloud/dcsdk/gettingstarted.html) and click on 'Get Started' to create your new credentials.

![Step 1](assets/GettingStartedJava_step1.png)

It's important to choose a 'Personal Account' to sign up for the free trial:

![Personal](assets/GettingStartedJava_personal.png)

In the next step you'll choose the PDF Services API Service, then add a name and description for your credentials.

There is a checkbox to 'Create personalized code sample'. Choose this option to have your new credentials automatically added to your sample files which will save you the manual step of adding them to your project. 

Next, choose Java as your language to receive the Java specific samples then click on the 'Create Credentials' button.

![Credentials](assets/GettingStartedJava_credentials.png)

You'll receive a .zip file to download called PDFToolsSDK-JavaSamples.zip which can be saved to your local file system. 

## Step 2: Setup your Java environment

1. Install [Java 8 or above](https://www.oracle.com/java/technologies/javase-downloads.html) if you haven't already.
1. Run `javac -version` to verify your install.
1. Verify the JDK bin folder is included in the PATH variable (method varies by OS).
1. Install [Maven](https://maven.apache.org/install.html) using your preferred tool if you haven't already.

The personalized samples provide everything from ready-to-run sample code, an embedded credential json file, and pre-configured connections to dependencies.

1. Download [the sample project](https://github.com/adobe/pdftools-java-sdk-samples).
1. Build the sample project with Maven: mvn clean install.
1. Test the sample code on the command line or in your preferred IDE.

## Final thoughts

The PDF Services API can help you eliminate manual processes by automating common workflows and shifting the processing burden to the cloud. In a world where every browser treats PDF differently, leveraging the Adobe PDF Embed API along with the PDF Services API, you can create streamlined, reliable, and predictable processes that run and display correctly **every time** regardless of platform or device.

## Resources and next steps

* For additional help and support, visit the Adobe [[!DNL Acrobat Services] APIs](https://community.adobe.com/t5/document-cloud-sdk/bd-p/Document-Cloud-SDK?page=1&sort=latest_replies&filter=all) community forum

* PDF Services API [Documentation](https://www.adobe.com/go/pdftoolsapi_doc)

* [FAQ](https://community.adobe.com/t5/contentarchivals/contentarchivedpage/message-uid/10726197) for PDF Services API questions

* [Contact us](https://www.adobe.com/go/pdftoolsapi_requestform) for questions on licensing and pricing

* Related articles

    [New PDF Services API offers even more features for document workflows](https://community.adobe.com/t5/acrobat-services-api-discussions/new-pdf-tools-api-brings-more-capabilities-for-document-services/m-p/11294170)

    [July Release of [!DNL Adobe Acrobat Services]: PDF Embed and PDF Services](https://medium.com/adobetech/july-release-of-adobe-document-services-pdf-embed-and-pdf-tools-17211bf7776d)
