---
title: SaveOptions.WarningHandler
second_title: Aspose.PDF for .NET API Reference
description: SaveOptions property. Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues however the user may also return Abort in which case the Save operation should cease
type: docs
weight: 40
url: /net/aspose.pdf/saveoptions/warninghandler/
---
## SaveOptions.WarningHandler property

Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### See Also

* interface [IWarningCallback](../../iwarningcallback/)
* class [SaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


