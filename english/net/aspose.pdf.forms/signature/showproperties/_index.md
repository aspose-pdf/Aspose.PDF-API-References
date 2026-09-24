---
title: "Signature.ShowProperties"
linktitle: "ShowProperties"
articleTitle: "ShowProperties"
second_title: "Aspose.PDF for .NET API Reference"
description: "Signature property. Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to r..."
type: docs
weight: 250
url: "/net/aspose.pdf.forms/signature/showproperties/"
product_version: "26.9.0"
---
## Signature.ShowProperties property

Force to show/hide signature properties.
 In case ShowProperties is true signature field has predefined format of appearance (strings to represent):
 -------------------------------------------
 Digitally signed by {certificate subject}
 Date: {signature.Date}
 Reason: {signature.Reason}
 Location: {signature.Location}
 -------------------------------------------
 where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image.
 ShowProperties is true by default.

```csharp
public bool ShowProperties { get; set; }
```

### Property Value

bool

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

