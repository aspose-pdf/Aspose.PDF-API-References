---
title: "Timestamp.Process"
linktitle: "Process"
articleTitle: "Process"
second_title: "Aspose.PDF for .NET API Reference"
description: "Timestamp method. Processes the timestamp plugin with the supplied options."
type: docs
weight: 20
url: "/net/aspose.pdf.lowcode/timestamp/process/"
product_version: "26.9"
---
## Timestamp.Process method

Processes the timestamp plugin with the supplied options.

```csharp
public ResultContainer Process(IPluginOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IPluginOptions | An options object containing inputs, outputs and timestamp settings. |

### Return Value

A [`ResultContainer`](../../resultcontainer/) with the operation results.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | If *options* is `null`. |
| InvalidOperationException | If *options* is not of type [`TimestampOptions`](../../timestampoptions/). |

### See Also

* class [ResultContainer](../../resultcontainer/)
* interface [IPluginOptions](../../ipluginoptions/)
* class [Timestamp](../)
* namespace [Aspose.Pdf.LowCode](../../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../../)

