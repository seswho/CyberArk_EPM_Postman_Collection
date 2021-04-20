# CyberArk_EPM_Postman_Collection
The CyberArk Endpoint Privilege Manager Web Services enable you to automate tasks that are usually performed manually in the EPM console.

## SDK Supported Platforms
The EPM Web Services SDK is a RESTful API that can be invoked by any RESTful client for various programming and scripting environments, including Java, C#, Perl, PHP, Python and Ruby.

## Using the EPM Web Services SDK
The EPM Web Services SDK enables you to perform activities on EPM objects via a REST Web Service interface. Each EPM object has its own URL path in the EPM website that can be accessed using the relevant HTTP/S request verb.

## Changes
**20 April 2021** - New postman collection based on the current version of CyberArk EPM
- Removed older versions of the collection with different names

**22 Jul, 2020** - Reformatting the collection 
- Rebuilt the collection based on the v11.6 CyberArk EPM Rest API documentation found at https://docs.cyberark.com/Product-Doc/OnlineHelp/EPM/Latest/en/Content/WebServices/API%20Commands.htm
- New Postman collection name: EPM.postman_environment.json
- v11.0 EPM RestAPI.postman_collection.json left for historical purposes

**22 Aug, 2019** - Reformatting the collection
- Renamed and rearranged the order based on the documentation at: https://documenter.getpostman.com/view/998920/RzZ9Gz1U?bs=true&version=latest#4b7b0681-3d90-4d67-b746-eb70e812be34
- Got tests working to fill in some of the environment variables i.e. the {{Address}}, {{Token}}, and {{Version}}. Not sure about adding tests for the other calls as they have the capability of returning more than one object in the response.

**21 Aug, 2019** - changes to README.md and v11.0 EPM RestAPI.postman_collection.json
- Modifications to v11.0 EPM RestAPI.postman_collection.json fixing the URLs changing {{Address}} to https://{{Address}} on the APIs where it was missing
- Changing the HTTP Method from POST to PUT on the Update Policy - For Ad Hoc User Elevation Policy only - "AdHocElevate" Policy type API call.
- Added a Test to the SaaS Server Version example API call to setup an environment variable called "Version"
- Include a Postman environment file to be imported and used with v11.0 EPM RestAPI.postman_collection.json

**20 Aug, 2019** - Initial commit of v11.0 EPM RestAPI.postman_collection.json
- The changes in the Postman collection in this repository reflect the new EPM Rest API capabilities to manage policies.

**6 May, 2019** - Repo creation
- The original version of this Postman collection can be found at https://github.com/ChuckMcAllister/CyberArk-EPM-REST-API-Postman-Collection
