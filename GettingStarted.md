## Getting Started

1. The sample projects for Tandem reside in a public GitHub repository (not the Autodesk enterprise GitHub).

	Access them here: [Tandem Samples](https://github.com/autodesk-tandem)
	You will need to send us your GitHub username or the email address used for public GitHub in order to gain access (these repos are marked private for now, so access is restricted).

	So far, there is one sample project for each of the three API contexts:
	- REST API via a node.js project
	- Embedded Viewer sample that uses the viewer and a Javascript SDK
	- Chrome browser extension (not supported, but provided for reference)

	Instructions for each project is in the README file on GitHub.  The Embedded Viewer sample is a good way to learn how Tandem works because it allows you to interactively select things in the model and see the underlying data structures.  You can have the Embedded Viewer sample and Tandem running side by side in different browser tabs and pointing at the same facility to compare how the product surfaces information with how the API does.

2. For the REST API, there is a Postman collection that is available to try out the functions interactively.  Here is a link to instructions on how to use that:  Tandem API - Postman instructions

3. The Postman collection has partial documentation for each function and usually a few example ways to call it.  However, some of the functions are not easy to figure out without a little extra guidance.  The main part of the API are functions to read/write individual property values.  There are extra notes explaining these functions in more depth.
	1. Read and query: /scan - Tandem API Docs - SCAN
	2. Write /mutate - Tandem API Docs - MUTATE
	3. Classification mapping - Tandem API - apply Parameters and Classifications
	4. Property mapping table - Tandem API Docs - /ATTRS, /SCHEMA

4. The main read/write functions will not be very interesting until you learn how to setup a Facility, Classification, and ParameterSets,  and then apply that Facility Template.  You can get started with the product by visiting: https://intandem.autodesk.com/

	Tim Kelly may be able to share a good demo facility with you if you have trouble getting one setup on your own.

Please route questions and feedback through James Awe, via email (james.awe@autodesk.com) or Slack #tandem-api (Autodesk internal only)
