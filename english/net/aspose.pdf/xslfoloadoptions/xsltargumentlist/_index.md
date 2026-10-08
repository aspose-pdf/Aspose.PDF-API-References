---
title: "XslFoLoadOptions.XsltArgumentList"
linktitle: "XsltArgumentList"
articleTitle: "XsltArgumentList"
second_title: "Aspose.PDF for .NET API Reference"
description: "XslFoLoadOptions property. XsltArgumentList for inserting values into existing xls parameters XLS file has 'animal' parameter without value: XsltArgumentList..."
type: docs
weight: 50
url: "/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/"
product_version: "26.9"
---
## XslFoLoadOptions.XsltArgumentList property

XsltArgumentList for inserting values into existing xls parameters 
 XLS file has 'animal' parameter without value: XsltArgumentList args = new XsltArgumentList();
 args.AddParam("animal", "", "cat"); now the converter assumes that there is an 'animal' parameter
 with the value 'cat' in the XLS file.

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

## Examples

XLS file has 'animal' parameter without value: XsltArgumentList args = new XsltArgumentList();
 args.AddParam("animal", "", "cat"); now the converter assumes that there is an 'animal' parameter
 with the value 'cat' in the XLS file.

### See Also

* class [XslFoLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

