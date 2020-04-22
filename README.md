# Encompass Integration with Notarize
### Introduction

To send Loans from Encompass to Notarize, an Encompass administrator has to upload the 
**Notarize eClosing Form** to your Encompass instance using Input Form Builder. In this repository, you will find the custom input form package named `NotarizeEClosing.empkg` under the *custom-forms* folder. It contains a set of custom field definitions used by the form to store transaction data from Notarize within Encompass loan.

You can download the latest NotarizeEclosing.empkg package from this repository. Your Encompass administrator can import the package using the Package Import Wizard inside the Input Form Builder.

If this is your first time to setup the integration, you will also need to import the Custom Data Object (CDO) that contains your Notarize API end point and API key to connect to your Notarize Lender Portal. You can obtain the CDO file directly from Notarize, or you can generate it yourself manually. The file has to be named as `notarize_config`, in json format. A sample file is attached to this repository as `notarize_config.sample`. Please substitute with your own api key, which you can generate within your lender portal, re-save the file and remove the `.sample` extension. The `notarize_config` CDO object can then be imported inside the Input Form Builder by your Encompass administrator.