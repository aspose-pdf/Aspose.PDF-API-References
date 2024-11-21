---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id class. Represents file identifier structure
type: docs
weight: 4450
url: /net/aspose.pdf/id/
---
## Id class

Represents file identifier structure.

```csharp
public class Id
```

## Properties

| Name | Description |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Changing identifier based on the document's contents at the time it was last updated. |
| [Original](../../aspose.pdf/id/original/) { get; } | Permanent identifier based on the contents of the document at the time it was originally created. |

## Examples

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


