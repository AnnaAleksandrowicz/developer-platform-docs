---
layout: page
title: Introduction to Kaltura's Client Libraries
weight: 106
---

>Note: This article applies to Kaltura API version 3 and later. It does not address how to implement specific flows using the Kaltura API.

## What are Kaltura's Kaltura Client Libraries?  

A Kaltura client library:

* Is an SDK package in a specific programming language
* Provides developers with easy access to the Kaltura API
* Makes it easy to develop Kaltura applications

The Kaltura client library is a collection of classes. Each class consists of objects and service classes. The collection of classes represents the entities, services, and actions that the Kaltura API provides.

## Why Should You Use a Kaltura Client Library?  

Kaltura recommends that you use a Kaltura Client Library when you develop applications that interact with the Kaltura API. Client libraries provide the following benefits:

* All objects and enums are auto-generated for you.
* All services and actions are auto-generated for you.
* Because they are auto-generated, there is lower chance for mistakes.
* The low level is already implemented for you, including:
	* HTTP communication
	* Serialization and de-serialization
	* Error handling
*  Authentication is built-in.
* Multi-request is built-in.
* Response-profile is built-in.
* Global parameters are utilized for you.


## What Are the Types of Client Libraries Available?  

There are different types of client libraries:

* Client libraries for the Kaltura Hosted Edition
* Local client libraries for Kaltura On-Prem™ and Kaltura Community Edition (Kaltura CE)
* Specialized Kaltura client libraries

To understand which type to use, see [Deciding Where to Get a Client Library](#DecidingontheRightTypeofClientLibrary).

## How Do You Start Using a Kaltura Client Library?  

First, [decide on the right type of client library](#DecidingontheRightTypeofClientLibrary). Then do one of the following:

* [Get a client library for Kaltura Hosted Edition][4].
* [Generate a client library for Kaltura On-Prem and Kaltura CE][5].
* [Generate a specialized Kaltura client library][6].

 [4]: #GettingaClientLibraryforKalturaHostedEdi
 [5]: #GeneratingaClientLibraryoaLocalServer
 [6]: #GeneratingaKalturaClientLibrary

When you have a client library:

* [Use the client library][3].
* Refer to [Sample Code for Multiple Client Library Languages][7] to help use your client library.

 [7]: #SampleCode

## Sample Code Usage  

All sample code is PHP5, unless otherwise stated.

The sample code is designed to show you how to use the features of Kaltura client libraries.

>Note: The sample code is formatted for this document and includes hard-coded examples. Before using sample code copied from this document, replace the examples and adapt the formatting.

## Document Conventions  

*   File paths and names appear in bold.  
    Example:** /[INSTALLATION_PATH]/app/generator/config.ini**

*   A string in brackets [] represents a value.  
    Replace the string – including the brackets – with an actual value.  
    Example: Replace *[yourClientLibraryName]* with *Java*.

## Client Library Programming Languages  

Kaltura provides [downloadable client libraries][8] for the Kaltura Hosted Edition in various programming languages. These languages also are available when [generating a client library for Kaltura On-Prem and Kaltura CE][5]. You can generate a client library for an additional language. See [Generating a Client Library for a Language that Kaltura Does Not Provide][9].

 [8]: https://developer.kaltura.com/api-docs/Client_Libraries
 [9]: https://knowledge.kaltura.com/adding-new-kaltura-api-client-library-generator

**Available Client Library Languages**

* PHP5
* Zend Framework-compatible library: Eases library integration in terms of coding standards and auto-loading
* JavaScript  
* Node.JS
* C# .NET       
* Java       
* Ruby       
* Python
* Objective-C/Cocoa
* Java Android
* CLI

## Where to Get a Client Library? 

The [type of client library][10] that you use depends on your Kaltura edition and specific needs.

 [10]: #WhatAretheTypesofClientLibraries

### Kaltura Hosted Edition  

If you use a standard Kaltura Hosted Edition, [get a client library for the Kaltura Hosted Edition][4].

### Kaltura On‑Prem  

If you use a standard Kaltura On‑Prem, you need local client libraries. See [Generating a Client Library for Kaltura On Prem and Kaltura CE][5].

### Kaltura CE  

If you use a standard Kaltura CE, you need local client libraries. See [Generating a Client Library for Kaltura On Prem and Kaltura CE][5].

<p class="mce-heading-3">
  <a name="GeneratingaClientLibraryforaLanguagethat"></a>Generating a Client Library for a Language that Kaltura Does Not Provide
</p>

If you want a client library for a language that Kaltura does not provide, you need to [generate a specialized Kaltura client library][6].

Kaltura welcomes contributions of client libraries for languages that Kaltura does not yet provide.

For more information, refer to [Kaltura API Usage Guidelines][11].

 [11]: http://knowledge.kaltura.com/kaltura-api-usage-guidelines

<p class="mce-heading-3">
  Using APIs from a Customized Server Plugin
</p>

If you want a client library to include customized APIs from a server plugin, you need to [generate a specialized Kaltura client library][6].

<p class="mce-heading-3">
  Using a Sub-Set of Kaltura APIs
</p>

If you want to use only a specific sub-set of Kaltura APIs without accessing other APIs, you need to [generate a specialized Kaltura client library][6].

<p class="mce-heading-3">
  <a name="GettingaClientLibraryforKalturaHostedEdi"></a>Getting a Client Library for Kaltura Hosted Edition
</p>

<p class="mce-heading-4">
  Who Uses Kaltura Hosted Client Libraries?
</p>

You need Kaltura Hosted client libraries if you use a standard Kaltura Hosted Edition.

If you use a different Kaltura edition, see [Generating a Client Library for Kaltura On-Prem and Kaltura CE][5].

If you have specialized needs, see [Generating a Specialized Kaltura Client Library][6].

<p class="mce-heading-4">
  How Is a Kaltura Hosted Client Library Generated?
</p>

Kaltura Hosted Edition client libraries are generated automatically based on the [schema][12] of the latest API version.

 [12]: http://www.kaltura.com/api_v3/api_schema.php

<p class="mce-note-graphic">
  Client libraries are updated automatically when Kaltura updates Hosted servers with a new API version.
</p>

<p class="mce-heading-4">
  How to Get a Kaltura Hosted Client Library?
</p>

Download client libraries from [Kaltura API SDK - Native Client Libraries][8].

<h1 class="mce-heading-1">
  <a name="GeneratingaClientLibraryoaLocalServer"></a>Generating a Client Library for Kaltura On‑Prem and Kaltura CE
</h1>

<p class="mce-heading-4">
  Who Generates Local Client Libraries?
</p>

You need to generate client libraries locally if you use standard Kaltura On-Prem or Kaltura CE.

If you use a standard Kaltura Hosted Edition, see [Getting a Client Library for Kaltura Hosted Edition][4].

If you have specialized needs, see [Generating a Specialized Kaltura Client Library][6].

<p class="mce-heading-4">
  Understanding Client Libraries and Self-Hosted Kaltura Servers
</p>

Kaltura On-Prem and Kaltura CE use self-hosted Kaltura servers.

Generating a client library locally ensures that the client library is compatible with the API version of the Kaltura edition on your self-hosted Kaltura server.

<p class="mce-heading-4">
  How Is a Kaltura Self-Hosted Client Library Generated?
</p>

If the version of your self-hosted edition is:

*   Dragonfly or earlier – Use the Kaltura server client generator to generate a client library locally.
*   Eagle or later – The Kaltura server client generator is executed automatically during installation.

<p class="mce-note-graphic">
  Do not generate a client library locally when you use an application developed by Kaltura or the community that is packaged with a client library. Changing the client library in the application may cause the application to fail.
</p>

<p class="mce-procedure">
  To generate a client library on your local Kaltura server:
</p>

(For Dragonfly and earlier versions of Kaltura self-hosted editions only:) Run the following script with root permissions: {% highlight bash %}cd /[INSTALLATION_PATH]/app/generator/ ./generate.sh{% endhighlight %} 

<p class="mce-note-graphic">
  The generator may not have permission to create the Kaltura client library files if you run the script without root permissions.
</p>

<h1 class="mce-heading-1">
  <a name="GeneratingaKalturaClientLibrary"></a>Generating a Specialized Kaltura Client Library
</h1>

<p class="mce-heading-3">
  Who Generates a Specialized Client Library?
</p>

You need to generate specialized client libraries if you want:

*   A client library for a language that Kaltura does not provide
*   A client library to include customized APIs from a server plugin
*   To use only a specific sub-set of Kaltura APIs without accessing other APIs

If you use a standard Kaltura Hosted Edition, see [Getting a Client Library for Kaltura Hosted Edition][4].

If you use a standard Kaltura On-Prem or Kaltura CE, see [Generating a Client Library for Kaltura On-Prem and CE][5].

<p class="mce-heading-3">
  Generating a Specialized Client Library – Overview
</p>

Generating a specialized client library may require:

*   Creating a language-specific *KalturaClientBase* class
*   Creating a language-specific generator class
*   Including a Kaltura server plugin in a generator
*   Modifying a generator **config.ini** file
*   Running a generator

The required steps depend on the purpose of your specialized client library.

<p class="mce-heading-3">
  Required Steps for Specialized Client Libraries
</p>

<table border="1" cellspacing="0" cellpadding="0">
  <thead>
    <tr>
      <td valign="top">
        <p>
          <strong>A New Language</strong>
        </p>
      </td>
      
      <td valign="top" width="227">
        <p>
          <strong>Including Server Plugin APIs</strong>
        </p>
      </td>
      
      <td valign="top" width="159">
        <p>
          <strong>API Sub-Set</strong>
        </p>
      </td>
    </tr>
  </thead>
  
  <tbody>
    <tr>
      <td valign="top">
        <p style="text-align: left;">
          <a href="#CreatingaLanguageSpecificKaltuaClientBas">Creating a Language-Specific KalturaClientBase Class</a>
        </p>
      </td>
      
      <td valign="top" width="227">
        <p style="text-align: left;">
          <a href="#IncludingaKalturaServerPlugininaGenerato">Including a Kaltura Server Plugin in a Generator</a>
        </p>
      </td>
      
      <td valign="top" width="159">
        <p style="text-align: left;">
          <a href="#Modifyingageneratorconfiginifile">Modifying a Generator config.ini File</a>
        </p>
      </td>
    </tr>
    
    <tr>
      <td style="text-align: left;" valign="top">
        <p>
          <a href="#CreatingaLanguageSpecificGeneratorClass">Creating a Language-Specific Generator Class</a>
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="227">
        <p>
          <a href="#RunningaGenerator">Running a Generator</a>
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="159">
        <p>
          <a href="#RunningaGenerator">Running a Generator</a>
        </p>
      </td>
    </tr>
    
    <tr>
      <td style="text-align: left;" valign="top">
        <p>
          <a href="#Modifyingageneratorconfiginifile">Modifying a Generator config.ini File</a>
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="227">
        <p>
           
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="159">
        <p>
           
        </p>
      </td>
    </tr>
    
    <tr>
      <td style="text-align: left;" valign="top">
        <p>
          <a href="#RunningaGenerator">Running a Generator</a>
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="227">
        <p>
           
        </p>
      </td>
      
      <td style="text-align: left;" valign="top" width="159">
        <p>
           
        </p>
      </td>
    </tr>
  </tbody>
</table>

<h2 class="mce-heading-2">
  How to Generate a Specialized Client Library
</h2>

<h3 class="mce-heading-3">
  Understanding the Client Library Generator
</h3>

The Kaltura system includes generator code that generates client libraries.

The generator:

*   Is written in PHP
*   Uses the *Zend_Reflection* class
*   Parses the entire Kaltura API code, including the PHP code comments
*   Generates a client library according to the services and actions in the Kaltura API

<h3 class="mce-heading-3">
  Understanding the KalturaClientBase class
</h3>

The *KalturaClientBase* class:

*   Contains all of the logic for communicating with the Kaltura API
*   Consists of methods for activities such as: 
    *   Submitting the HTTP request to the Kaltura API
    *   Building the HTTP request from objects
    *   Parsing the API output (from XML or other output format) back in to the response object,
    *   Writing logs

*   Is independent of most Kaltura API services and actions
*   Is written manually for each client library

<h3 class="mce-heading-3">
  Understanding the Kaltura Client Library Generator Class
</h3>

Each client library is generated using a language‑specific generator class.

The generator class has methods that are required to be implemented so that the code output is in the relevant language.

The generator class includes methods such as:

*   *writeEnum* –Outputs code of an enumeration class (for example, [KalturaEntryStatus](https://developer.kaltura.com/api-docs/General_Objects/Enums/KalturaEntryStatus))
*   *writeClass* – Outputs code of an object that represents a Kaltura entity (for example, [KalturaBaseEntry](https://developer.kaltura.com/api-docs/General_Objects/Objects/KalturaBaseEntry))
*   *writeService* - Outputs code of an object that represents a Kaltura service.  
    The object has methods. Each method represents an action that is available in the service.
*   *writeAction* - Outputs code of an action method within a service object.

A generator's methods collectively generate the code of an entire language‑specific client library.

A generator class is written in PHP.

The generator class structure usually is the same for all languages.

The main difference between generator classes is the method outputs.

<p class="mce-heading-4">
  Required Developer Knowledge
</p>

A developer who writes a language‑specific generator requires:

*   Wide knowledge of the language of the generated client library
*   Familiarity with the language's limitations and behaviors.  
    For example, whether the language supports nullable Boolean values.

<h3 class="mce-heading-3">
  Understanding Inclusion of a Kaltura Server Plugin in a Client Library
</h3>

The Kaltura server supports extending the API with server plugins. Kaltura server plugins can provide new API services.

A server plugin usually contains a configuration file that includes the plugin in a client library.

A generator places all server plugin APIs in separate files.

The server can disable a server plugin. Similarly, a client library can exclude a server plugin by excluding the server plugin API files.

<p class="mce-heading-4">
  Coding Standard Compliance
</p>

When you write a Kaltura server plugin that extends the Kaltura API, Kaltura strongly recommends that you follow Kaltura API coding standards. A generator can handle server plugins for a client library accurately only if the plugin services comply with API coding standards, including code comments.

<h3 class="mce-heading-3">
  Understanding the Generator config.ini File
</h3>

A generator refers to a **config.ini** file during execution.

The **config.ini**:

*   Specifies the client library package to generate
*   Specifies the services and actions to include or exclude
*   Is located in **[INSTALLATION_PATH]/app/generator/config.ini**

<h2 class="mce-heading-2">
  Producing a Specialized Kaltura Client Library
</h2>

<h3 class="mce-heading-3">
  <a name="CreatingaLanguageSpecificKaltuaClientBas"></a>Creating a Language-Specific KalturaClientBase Class
</h3>

<p class="mce-procedure">
  To create a language-specific KalturaClientBase class:
</p>

1.  [Download a client library][8] for an existing language.
2.  Base the language-specific class on a *KalturaClientBase* class in the downloaded client library.  
    *KalturaClientBase* is located in **/[INSTALLATION\_PATH]/app/generator/sources/[LANGUAGE\_NAME]/**

<h3 class="mce-heading-3">
  <a name="CreatingaLanguageSpecificGeneratorClass"></a>Creating a Language-Specific Generator Class
</h3>

<p class="mce-procedure">
  To create a custom language-specific generator class:
</p>

1.  [Download a client library][8] for an existing language.
2.  Base the language-specific class on a generator class in the downloaded client library.  
    An example of a generator class path and name is: **/[INSTALLATION_PATH]/app/generator/JavaClientGenerator.php**

<h3 class="mce-heading-3">
  <a name="IncludingaKalturaServerPlugininaGenerato"></a>Including a Kaltura Server Plugin in a Generator
</h3>

<p class="mce-procedure">
  To include a Kaltura Server Plugin in a generator:
</p>

In your Kaltura server plugin, include a configuration that defines the plugin services included in client libraries.

The client library generator refers to the plugin configuration. The generator includes or excludes plugin services in the generated client libraries as specified in the plugin configuration.

<p class="mce-note-graphic">
  Do not modify the generator config.ini file to include or exclude plugin services.
</p>

<h3 class="mce-heading-3">
  <a name="Modifyingageneratorconfiginifile"></a>Modifying a Generator config.ini File
</h3>

<p class="mce-procedure">
  To include specific services and actions in the generator config.ini file:
</p>

1.  Open **/[INSTALLATION_PATH]/app/generator/config.ini**.
2.  For the language you are generating:
*   Add an *include* command with the services and actions to include. For example:  
    {% highlight bash %}include = batch.*, batchcontrol.*, jobs.*, media.addfrombulk{% endhighlight %} An asterisk includes all of a service's actions. For example, *batch.** includes all *batch* service actions.  
    Specifying a service and action includes only the specific action of the service. For example, *media.addfrombulk* includes only the *addfrombulk* action of the *media* service.
*   If an *include* command exists, add to the command the services and actions you want to include.

3.  Save the file.

<p class="mce-procedure">
  To exclude specific services and actions from the generator config.ini file:
</p>

1.  Open **/[INSTALLATION_PATH]/app/generator/config.ini**.
2.  For the language you are generating:
*   Add an *exclude* command with the services and actions to exclude. For example:  
    {% highlight bash %}exclude = batch.*, batchcontrol.*, jobs.*, media.addfrombulk{% endhighlight %} An asterisk excludes all of a service's actions. For example, *batch.** excludes all *batch* service actions.  
    Specifying a service and action excludes only the specific action of the service. For example, *media.addfrombulk* excludes only the *addfrombulk* action of the *media* service.
*   If an *exclude* command exists, add to the command the services and actions you want to exclude.

3.  Save the file.

<p class="mce-procedure">
  To include your client library in the generator config.ini file:
</p>

1.  Open **/[INSTALLATION_PATH]/app/generator/config.ini**.
2.  Add a section that specifies:
<ol style="list-style-type: lower-alpha;">
  <li>
    The client library name <br /> For example, when generating a client library in a new language, typically you use the language name.
  </li>
  <li>
    The generator class name
  </li>
</ol>

3.  Save the file.

Example of the section to add: {% highlight bash %}[yourClientLibraryName] generator = [classNameOfYourGenerator]{% endhighlight %} 

<h3 class="mce-heading-3">
  <a name="RunningaGenerator"></a>Running a Generator
</h3>

<p class="mce-procedure">
  To generate a client library on your local Kaltura server:
</p>

Run the following script with root permissions: {% highlight bash %}cd /[INSTALLATION_PATH]/app/generator/ ./generate.sh {% endhighlight %} 

<p class="mce-note-graphic">
  The generator may not have permission to create the Kaltura client library files if you run the script without root permissions.
</p>

Your client library will be located under the output folder. For example: **/[INSTALLATION_PATH]/web/content/clientslibs/[yourClientLibraryName]/**

<h1 class="mce-heading-1">
  <a name="UsingaKalturaClientLibrary"></a>Using a Kaltura Client Library
</h1>

Using a client library requires:

1.  [Including a Client Library in an Application][13]
2.  [Instantiating a Client Object][14]

 [13]: #IncludingaClientLibraryinanApplication
 [14]: #InstantiatingaClientObject

Using a client library may include:

*   [Using a Client Object to Perform an API Call][15]
*   [Performing Multi-Requests][16]
*   [Error Handling][17]

 [15]: #UsingaClientObjecttoPerformanAPICall
 [16]: #PerformingaMultiRequest
 [17]: #ErrorHandling

See [Tips and Tricks][18] for resources related to using a client library.

 [18]: #TipsandTricks

For sample code in available client library languages, see [Sample Code for Multiple Client Library Languages][7].

## Including a Client Library in an Application

Before you can use a client library, you include the client library in your application.

Depending on your programming language and application setup, either:

*   You explicitly include the client library in your application.
*   Your environment automatically includes the client library in your application using a feature such as the PHP auto-loading capability.

The client library files included in your application depend on the client library generator. Usually you include only the *KalturaClient* file.

The *KalturaClient* file is the main class that includes:

*   All other classes (including *KalturaClientBase*)
*   Most core Kaltura APIs: 
    *   Entity objects
    *   Enumeration objects
    *   Filter objects
    *   Service classes
    *   Service class methods

To explicitly include a client library in your application:

Implement the following code in your application: 
{% highlight php %}
<?php 
require_once 'KalturaClient.php';
{% endhighlight %}

## Excluding a Server Plugin from an Application

All APIs that belong to a Kaltura server plugin are generated in separate files.

The server can disable a server plugin. Similarly, a client library can exclude a server plugin by excluding the server plugin API files.

To exclude a server plugin from an application:

Do not include the server plugin API files in the client library.

## Instantiating a Client Object

Before you can use a client library, you need a client object to perform actions with the Kaltura API.

Depending on your use case, you may need to instantiate client objects multiple times.

Instantiating a client object requires:

1.  [Creating a configuration object][19]
2.  [Starting a Kaltura session][20]
3.  [Setting the Kaltura session for the configuration object][21]

 [19]: #CreatingaConfigurationObject
 [20]: #StartingaKalturaSession
 [21]: #SettingtheKalturaSessionfortheConfigurat

## Creating a Configuration Object

To create a configuration object for a client library:

Include the following code:

```php
<?php
$kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID 
$kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is  other than the default http://www.kaltura.com
$kalturaClient = new KalturaClient($kalturaConfig);
```

## Starting a Kaltura Session

You need to start a Kaltura session (KS) before using a client object for most API calls.

For more information about a KS, refer to [Kaltura API Usage Guidelines][11].

To create a KS:

Implement the following code:

```
<?php
$ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges);
```

Setting the Kaltura Session for the Configuration Object

To set the KS for the configuration object:

Implement the following code: 
{% highlight php %}
$kalturaClient->setKs($ks);
{% endhighlight %} 

Using a Client Object to Perform an API Call

The Kaltura API structure consists of a list of services, represented by service objects. Each service object consists of different actions, represented by a method in the service object.

For example:

1.  To call the *media* service to get a specific media entry instance from the Kaltura server entry, you use the *get* action.  
    The result of *media.get* is an object of type [KalturaMediaEntry][22].
2.  After performing the *media.get* call, you print the name of the entry.

 [22]: https://developer.kaltura.com/api-docs/#/KalturaMediaEntry

For more information about the Kaltura API structure, refer to <a href="http://knowledge.kaltura.com/kaltura-api-usage-guidelines">Kaltura API Usage Guidelines</a>.

To perform a media.get call:

Implement the following code: 
{% highlight php %}
$entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have 
$mediaEntry = $client->media->get($entryId);
{% endhighlight %} 

To print the name of the media entry:

Implement the following code: 
{% highlight php %}
echo $mediaEntry->name;
{% endhighlight %} 

Example Workflow

An example workflow for printing a known media item's name from a client library involves:

1.  [Including a Client Library in an Application][13]
2.  [Instantiating a Client Object][14]
<ol style="list-style-type: lower-alpha;">
  <li>
    <a href="#CreatingaConfigurationObject">Creating a configuration object</a>
  </li>
  <li>
    <a href="#StartingaKalturaSession">Starting a Kaltura session</a>
  </li>
  <li>
    <a href="#SettingtheKalturaSessionfortheConfigurat">Setting the Kaltura session for the configuration object</a>
  </li>
</ol>

3.  [Using a Client Object to Perform an API Call][15]<ol style="list-style-type: lower-alpha;">
      <li>
        <a href="#Toperformamediagetcall">Performing a media.get call</a>
      </li>
      <li>
        <a href="#Toprintthenameofthemediaentry">Printing the name of the media entry</a>
      </li>
    </ol>

<p class="mce-heading-3">
  Sample Code for Printing a Known Media Item's Name:
</p> {% highlight php %}require_once 'KalturaClient.php'; $kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID $kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is // other than the default http://www.kaltura.com $kalturaClient = new KalturaClient($kalturaConfig); $ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges); $kalturaClient->setKs($ks); $entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have $mediaEntry = $client->media->get($entryId); echo $mediaEntry->name;{% endhighlight %} 

<h3 class="mce-heading-3">
  Performing an API Call with a Server-Side Plugin Service
</h3>

Plugin APIs (services and objects) are generated in separate files. You can remove API files from the package easily without breaking inner dependency. See [Excluding a Server Plugin from an Application][23].

 [23]: #ExcludingaServerPluginfromanApplication

Since plugin APIs are not included in an application as a generic part of the client library, you use plugin APIs differently than client library objects.

To perform a call using a plugin's metadata API:

Implement the following code: 
{% highlight php %}
require_once 'KalturaClient.php'; 
$kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID 
$kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
$kalturaClient = new KalturaClient($kalturaConfig); 
$ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges); 
$kalturaClient->setKs($ks); 
$entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have instantiating a filter object required for the API call. 
$metadataFilter = new KalturaMetadataFilter(); // 1111 is a known ID of metadata profile 
$metadataFilter->metadataProfileIdEqual = '1111'; 
$metadataFilter->metadataObjectTypeEqual = KalturaMetadataObjectType::ENTRY; // filtering metadata objects for specific entry: 
$metadataFilter->objectIdEqual = $entryId; // instantiating a plugin object which holds its own services. note that we pass the client to the plugin object 
$metadataPlugin = KalturaMetadataClientPlugin::get($kalturaClient); // calling the specific service 'metadata' and a specific action 'list'
$metadataForEntry = $metadataPlugin->metadata->listAction($metadataFilter); 
var_dump($metadataForEntry);
{% endhighlight %} 

Performing Multi-Requests

The Kaltura API supports the multi-request feature.

The multi-request feature allows you to stack multiple required calls and issue them in a single HTTP request. The multi-request feature reduces the number of network round trips between your server and Kaltura.

You instruct the client to start a multi-request stack of calls. When all of the required calls are stacked, you instruct the client to perform the actual HTTP request.

The multi-request feature supports the ability to have one request depend on the result of another request.

For more information about the multi-request feature, refer to <a href="http://knowledge.kaltura.com/kaltura-api-usage-guidelines">Kaltura API Usage Guidelines</a>.

To perform a multi-request:

Implement code based on the following example: 
{% highlight php %}
require_once 'KalturaClient.php'; 
$kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID 
$kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
$kalturaClient = new KalturaClient($kalturaConfig); 
$ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges); 
$kalturaClient->setKs($ks); $entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have 
try { // tell the client to start stacking actions for multi-request 
  $kalturaClient->startMultiRequest(); // add first call to multi-request stack 
  $kalturaClient->media->get($entryId); // create empty object for updating 
  $emptyEntryForUpdate = new KalturaMediaEntry(); // set dependency between second call and first call, the description to be set on the entry is the tags from the previous 'media.get' call 
  $emptyEntryForUpdate->description = '{1:result:tags}'; // add second call to multi-request stack 
  $kalturaClient->media->update($entryId, $emptyEntryForUpdate); // tell the client to perform the actual HTTP request for the stacked actions 
  $results = $kalturaClient->doMultiRequest(); // extract result objects from array of results 
  $mediaEntry = $results[0]; 
  $updatedMediaEntry = $results[1]; 
  echo "entry tags: " . $mediaEntry->tags; 
  echo "new entry desription: " . $updatedMediaEntry->description; 
} catch(Exception $ex) { 
  echo "could not get entry from Kaltura. Reason: " . $ex->getMessage(); 
}
{% endhighlight %} 

Error Handling

The Kaltura API can return errors.

The API follows object-oriented programming (OOP) principles. A client library is generated as OOP code that consists of classes and methods. The best way for a client library to handle errors natively is by using exceptions, as follows:

A client library parses an API output. If the API returned an error, the client throws an exception that includes the error code and message that the Kaltura server returned.

Kaltura recommends that you wrap API calls in your code in a *try-catch* block to enable user-friendly error handling. This approach prevents your application from crashing.

For more information about Kaltura API error handling, refer to <a href="http://knowledge.kaltura.com/kaltura-api-usage-guidelines">Kaltura API Usage Guidelines</a>.

API Error Handling – Sample Code

The following is an example of error handling for printing a known media item's name: 
{% highlight perl %}
require_once 'KalturaClient.php'; 
$kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID 
$kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
$kalturaClient = new KalturaClient($kalturaConfig); 
$ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges); 
$kalturaClient->setKs($ks); 
$entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have 
try { 
    $mediaEntry = $client->media->get($entryId); 
    echo $mediaEntry->name; 
} catch(Exception $ex) { 
    echo "could not get entry from Kaltura. Reason: " . $ex->getMessage(); 
}
{% endhighlight %} 

<h2 class="mce-heading-2">
  <a name="TipsandTricks"></a>Tips and Tricks
</h2>

*   To learn about the Kaltura API, refer to the [Kaltura API Test Console][24].
*   In the [Kaltura API Test Console][24], you can toggle between PHP, Java, and C# to display a code example.
*   To learn about specific services, actions, and objects, refer to the [API documentation][25].
*   For examples used in this document in languages available in the [Kaltura API SDK - Native Client Libraries][8], see [Sample Code for Multiple Client Library Languages][7].

 [24]: https://developer.kaltura.com/console 
 [25]: https://developer.kaltura.com/api-docs

<h1 class="mce-heading-1">
  <a name="SampleCode"></a>Sample Code for Multiple Client Library Languages
</h1>

The sample code demonstrates the following scenario for using a Kaltura client library:

1.  [Including a Client Library in an Application][13]
2.  [Instantiating a Client Object][14]
<ol style="list-style-type: lower-alpha;">
  <li>
    <a href="#CreatingaConfigurationObject">Creating a configuration object</a>
  </li>
  <li>
    <a href="#StartingaKalturaSession">Starting a Kaltura session</a>
  </li>
  <li>
    <a href="#SettingtheKalturaSessionfortheConfigurat">Setting the Kaltura session for the configuration object</a>
  </li>
</ol>

3.  [Using a Client Object to Perform an API Call][15] (*media.get*)
<ol style="list-style-type: lower-alpha;">
  <li>
    <a href="#Toperformamediagetcall">Performing a media.get call</a>
  </li>
  <li>
    <a href="#Toprintthenameofthemediaentry">Printing the name of the media entry</a>
  </li>
</ol>

4.  [Error Handling][17]

To understand the sample code in detail, see [Using a Kaltura Client Library][3].

## Sample Code – Available Languages

Sample code appears for the following languages:

* PHP
* Java
* C#
* Python
* Ruby
* AS3
* JavaScript
* Objective-C/Cocoa

### PHP5

{% highlight perl %}
require_once 'KalturaClient.php'; 
$kalturaConfig = new KalturaConfiguration(123); // where 123 is your partner ID 
$kalturaConfig->serviceUrl = 'http://KalturaServerDomain'; // if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
$kalturaClient = new KalturaClient($kalturaConfig); 
$ks = $kalturaClient->generateSession($adminSecret, $userId, KalturaSessionType::ADMIN, $partnerId, $expiry,$privileges); 
$kalturaClient->setKs($ks); 
$entryId = 'XXXYYYZZZA'; // a known ID of media entry that you have 
try { 
    $mediaEntry = $client->media->get($entryId); 
    echo $mediaEntry->name; 
} catch(Exception $ex) { 
    echo "could not get entry from Kaltura. Reason: " . $ex->getMessage(); 
}
{% endhighlight %} 

### Java  

{% highlight java %}
package com.kaltura.code.example; 
import com.kaltura.client.enums.*; 
import com.kaltura.client.types.*; 
import com.kaltura.client.services.*; 
import com.kaltura.client.KalturaApiException; 
import com.kaltura.client.KalturaClient; 
import com.kaltura.client.KalturaConfiguration; 
class CodeExample
{ 
    public static void main(String[] args)
    { 
	KalturaConfiguration config = new KalturaConfiguration(); 
	config.setPartnerId(123); // where 123 is your partner ID config.setEndpoint("http://www.kaltura.com/"); if you want to communicate with a Kaltura server which isother than the default http://www.kaltura.com 
	KalturaClient client = new KalturaClient(config); 
	String entryId = null; 
	int version = 0; 
	String ks = client.generateSession( adminSecret, userId, type, partnerId, expiry, privileges ); 
	client.setSessionId(ks); entryId = "XXXYYYZZZA"; // a known ID of media entry that you have 
	try{ 
	    KalturaMediaEntry mediaEntry = client.getMediaService().get(entryId); 
	    System.out.print(mediaEntry.getName()); 
	}catch(KalturaApiException e){ 
	    System.out.print("could not get entry from Kaltura. Reason: "); e.printStackTrace(); 
	} 
    } 
}
{% endhighlight %} 

### C\#

{% highlight csharp %}
using System.Collections.Generic; 
using System.Text; 
using System.IO; 
namespace Kaltura
{ 
    class CodeExample
    { 
	static void Main(string[] args)
	    { 
		KalturaConfiguration config = new KalturaConfiguration(123); // where 123 is your partner ID 
		config.ServiceUrl = "http://www.kaltura.com/"; // if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
		KalturaClient client = new KalturaClient(config); 
		String ks = client.GenerateSession( adminSecret, userId, type, partnerId, expiry, privileges ); // GenerateSession method is already implemented in the C# library 
		String entryId = null; 
		int version = 0; 
		client.KS = ks; 
		entryId = "XXXYYYZZZA"; // a known ID of media entry that you have 
		try { 
		    KalturaMediaEntry mediaEntry = client.MediaService.Get(entryId); 
		    System.Console.WriteLine(mediaEntry.name); 
		} catch(KalturaException ex) { 
		    System.Console.WriteLine("could not get entry from Kaltura. "); 
		    System.Console.WriteLine("Reason: "); System.Console.WriteLine(ex.toString()); 
		} 
	    } 
    } 
}
{% endhighlight %} 

### Python  

{% highlight python %}
from KalturaClient import * 
config = KalturaConfiguration(123) # where 123 is your partner ID 
config.serviceUrl = "http://devtests.kaltura.co.cc/" # if you want to communicate with a Kaltura server which is other than the default http://www.kaltura.com 
client = KalturaClient(config) 
ks = client.generateSession(adminSecret, userId, type, partnerId, expiry, privileges) 
client.setKs(ks) 
entryId = "XXXYYYZZZA"; # a known ID of media entry that you have 
try: 
    mediaEntry = client.media.get(entryId) 
    print mediaEntry.getName() 
except KalturaException, e: 
    print "could not get entry from Kaltura. Reason: %s" % repr(e)
{% endhighlight %} 

### Ruby  

{% highlight ruby %}
require "ruby_client.rb" 
include Kaltura 
config = KalturaConfiguration.new(123) # where 123 is your partner ID 
config.service_url = 'http://www.kaltura.com/' # if you want to communicate with a Kaltura server which is 
# other than the default http://www.kaltura.com 
client = KalturaClient.new(config) 
ks = client.session_service.start (secret, userId, type, partnerId, expiry, privileges) 
client.ks = ks entry_id = 'XXXYYYZZZA' 
media_entry = client.media_service.get(entry_id) 
puts media_entry.name
{% endhighlight %} 

>Note: The Ruby client library does not include a local generateSession function to generate a Kaltura session. Instead, use the session service to start a session.

### AS3  

{% highlight c %}
{ import com.kaltura.KalturaClient; import com.kaltura.commands.baseEntry.BaseEntryGet; import com.kaltura.config.KalturaConfig; import com.kaltura.events.KalturaEvent; public class CodeExample { private var \_client:KalturaClient; public function CodeExample() { // create KalturaClient: var configuration:KalturaConfig = new KalturaConfig(); configuration.partnerId = "123"; // where 123 is your partner ID configuration.ignoreNull = 1; configuration.ks = loaderInfo.parameters.ks; // ks passed in as flashvar \_client = new KalturaClient(configuration); var entryId:String = "XXXYYYZZZA"; // a known ID of media entry that you have var beg:BaseEntryGet = new BaseEntryGet(entryId); beg.addEventListener(KalturaEvent.COMPLETE, handleEntryGet); beg.addEventListener(KalturaEvent.FAILED, handleEntryGet); _client.post(beg); } private function handleEntryGet(e:KalturaEvent):void { e.target.removeEventListener(KalturaEvent.COMPLETE, handleEntryGet); e.target.removeEventListener(KalturaEvent.FAILED, handleEntryGet); if (e.type == KalturaEvent.COMPLETE) { trace(e.data.name); } else { trace("could not get entry from Kaltura. Reason: ", e.error.errorMsg); } } } }
{% endhighlight %} 

### JavaScript  
 

{% highlight javascript %}
<script type="text/javascript"> 
var kConfig; 
var kClient; 
var partnerId = 123; // where 123 is your partner ID 
var userId = "someone"; 
var expiry = 86400; var privileges = ""; // call server side to generate a KS for you so secrets will not be compromised 
var ks = ajaxGetKs(partnerId, userId, expiry, privileges); 
var entryId = "XXXYYYZZZA"; // a known ID of media entry that you have 
function pageLoad() 
{ 
    kConfig = new KalturaConfiguration(partnerId); 
    kConfig.serviceUrl = "http://www.kaltura.com"; // if you want to communicate with a Kaltura server which is 
    // other than the default http://www.kaltura.com 
    kClient = new KalturaClient(kConfig); 
    kClient.ks = ks; 
    getEntrySample(); 
    return false; 
} 
function getEntrySample() 
{ 
    kClient.media.get(getEntryResult, entryId); 
} 
function getEntryResult(success, data) 
{ 
    if (data.code) { 
	alert("Error: "+data.message); 
    } else { 
	alert("Your entry name: "+data.name); 
    } 
} 
</script>
{% endhighlight %} 

#### Handling Secrets  

Because JavaScript is a client-side programming language, secrets included in the code are compromised. Exposing secrets causes a security issue.

To avoid exposing the KS secret, Kaltura recommends calling an AJAX (or similar methodology) server‑side action that returns a KS. The sample code implements the recommendation: 

{% highlight javascript %}
var ks = ajaxGetKs(partnerId, userId, expiry, privileges);
{% endhighlight %} 

For more information about security issues related to accessing the Kaltura API using client-side technology, refer to [Kaltura API Authentication and Security](/api-docs/VPaaS-API-Getting-Started/Kaltura_API_Authentication_and_Security.html).

### Objective-C/Cocoa  

{% highlight objc %}
#import "KalturaClient.h" 
#define SERVICE_URL (@"http://www.kaltura.com") 
#define ADMIN_SECRET (@"1234abcd") 
#define PARTNER_ID (1234) 
#define USER_ID (@"user") 
#define ENTRY_ID (@"0_12345678") 
@interface GetEntrySample : NSObject - (void)sample; @end @implementation GetEntrySample - (void)sample 
{ 
    KalturaClientConfiguration* config = [[KalturaClientConfiguration alloc] init]; 
    config.serviceUrl = SERVICE_URL; 
    KalturaNSLogger* logger = [[KalturaNSLogger alloc] init]; 
    config.logger = logger; 
    [logger release]; // retained on config 
    config.partnerId = PARTNER_ID; 
    KalturaClient* client = [[KalturaClient alloc] initWithConfig:config]; 
    [config release]; // retained on the client 
    client.ks = [KalturaClient generateSessionWithSecret:ADMIN_SECRET withUserId:USER_ID withType:[KalturaSessionType ADMIN] withPartnerId:PARTNER_ID withExpiry:86400 withPrivileges:@""]; 
    KalturaMediaEntry* mediaEntry = [client.media getWithEntryId:ENTRY_ID]; 
    if (client.error != nil) NSLog(@"Failed to get entry, domain=%@ code=%d", error.domain, error.code); 
    else NSLog(@"Entry name %@", mediaEntry.name); [client release]; 
} 
@end
{% endhighlight %}
