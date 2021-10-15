# Snork.Model.Rdl2016
[![Latest version](https://img.shields.io/nuget/v/Snork.Model.Rdl2016.svg)](https://www.nuget.org/packages/Snork.Model.Rdl2016/) 

This is an object data model can be used to serialize/deserialize files in Microsoft's XML-based Report Definition Language, version 2016.

To use this model, you'll use an XmlSerializer instance:

 - To READ: Provide a readable stream to the XmlSerializer and use its Deserialize method with type Snork.Model.Rdl2016.Report.
 - To WRITE: Provide a writable stream to the XmlSerializer and use its Serialize method with type Snork.Model.Rdl2016.Report.
