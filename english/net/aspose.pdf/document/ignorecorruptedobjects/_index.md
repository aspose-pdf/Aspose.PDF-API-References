---
title: "Document.IgnoreCorruptedObjects"
linktitle: "IgnoreCorruptedObjects"
articleTitle: "IgnoreCorruptedObjects"
second_title: "Aspose.PDF for .NET"
description: "Gets or sets flag of ignoring errors in source files. When pages from source document copied into destination document, copying process is stopped with excep..."
type: docs
weight: 1570
url: "/net/aspose.pdf/document/ignorecorruptedobjects/"
product_version: "26.9.0"
---
## Document.IgnoreCorruptedObjects property

Gets or sets flag of ignoring errors in source files. 
 When pages from source document copied into destination document, copying process is stopped with exception 
 if some objects in source files are corrupted when this flag is false. 
 example: dest.Pages.Add(src.Pages);
 If this flag is set to true then corrupted objects will be replaced with empty values.
 By default: true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Property Value

bool

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

