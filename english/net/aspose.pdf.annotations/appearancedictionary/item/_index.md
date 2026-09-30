---
title: "AppearanceDictionary.Item"
linktitle: "Item"
articleTitle: "Item"
second_title: "Aspose.PDF for .NET API Reference"
description: "AppearanceDictionary property. Represents convenient form for getting appearance streams."
type: docs
weight: 190
url: "/net/aspose.pdf.annotations/appearancedictionary/item/"
product_version: "26.9.0"
---
## AppearanceDictionary indexer

Represents convenient form for getting appearance streams.

```csharp
public XForm this[string key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | Represents path to appearance stream. 
 If appearance dictionary has subdictionaries, then path must contain 2 parts (<see cref="P:Aspose.Pdf.Annotations.AppearanceDictionary.Keys" />), 
 else path has only one part. |

### Return Value

XForm object (appearance stream) which corresponds to the given key.

### See Also

* class [XForm](../../../aspose.pdf/xform/)
* class [AppearanceDictionary](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

