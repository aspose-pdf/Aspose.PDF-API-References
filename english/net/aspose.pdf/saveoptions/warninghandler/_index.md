---
title: "SaveOptions.WarningHandler"
linktitle: "WarningHandler"
articleTitle: "WarningHandler"
second_title: "Aspose.PDF for .NET"
description: "Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default act..."
type: docs
weight: 20
url: "/net/aspose.pdf/saveoptions/warninghandler/"
product_version: "26.9.0"
---
## SaveOptions.WarningHandler property

Callback to handle any warnings generated. 
 The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. 
 Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### Property Value

[IWarningCallback](../../../aspose.pdf/iwarningcallback/)

### See Also

* class [IWarningCallback](../../../aspose.pdf/iwarningcallback/)
* class [SaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

