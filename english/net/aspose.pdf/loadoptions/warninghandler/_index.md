---
title: "LoadOptions.WarningHandler"
linktitle: "WarningHandler"
articleTitle: "WarningHandler"
second_title: "Aspose.PDF for .NET API Reference"
description: "LoadOptions property. Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Conti..."
type: docs
weight: 20
url: "/net/aspose.pdf/loadoptions/warninghandler/"
product_version: "26.9.0"
---
## LoadOptions.WarningHandler property

Callback to handle any warnings generated. 
 The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. 
 Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### Property Value

[IWarningCallback](../../../aspose.pdf/iwarningcallback/)

### See Also

* class [IWarningCallback](../../../aspose.pdf/iwarningcallback/)
* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

