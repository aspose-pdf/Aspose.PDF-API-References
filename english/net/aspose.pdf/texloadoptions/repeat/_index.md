---
title: "TeXLoadOptions.Repeat"
linktitle: "Repeat"
articleTitle: "Repeat"
second_title: "Aspose.PDF for .NET API Reference"
description: "TeXLoadOptions property. Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case, for example, there are references in input T..."
type: docs
weight: 70
url: "/net/aspose.pdf/texloadoptions/repeat/"
product_version: "26.9.0"
---
## TeXLoadOptions.Repeat property

Gets/sets the flag indicating whether it is necessary to run the TeX job twice in case,
 for example, there are references in input TeX file(s). In general, this behavior is useful when
 the engine collects some data along the typesetting process and stores it in an auxilliary file,
 all at the first run. And at the second run, the engine somehow uses that data.

```csharp
public bool Repeat { get; set; }
```

### Property Value

bool

### See Also

* class [TeXLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

