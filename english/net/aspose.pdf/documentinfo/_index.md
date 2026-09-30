---
title: "DocumentInfo Class"
linktitle: "DocumentInfo"
articleTitle: "DocumentInfo"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.DocumentInfo class. Represents meta information of PDF document."
type: docs
weight: 700
url: "/net/aspose.pdf/documentinfo/"
keywords: "DocumentInfo, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DocumentInfo class

Represents meta information of PDF document.

```csharp
public sealed class DocumentInfo : Dictionary<string, string>
```

## Constructors

| Name | Description |
| --- | --- |
| [DocumentInfo](./documentinfo/)(Document) | Initialize DocumentInfo instance. |

## Properties

| Name | Description |
| --- | --- |
| [Author](./author/) { get; set; } | Gets or sets document author. |
| [CreationDate](./creationdate/) { get; set; } | Gets or sets the date of document creation. |
| [CreationTimeZone](./creationtimezone/) { get; set; } | Time zone of creation date. |
| [Creator](./creator/) { get; set; } | Gets or sets document creator. |
| [Item](./item/) { get; set; } | Gets or sets the value associated with the specified key. |
| [Keywords](./keywords/) { get; set; } | Gets or set the keywords of the document. |
| [ModDate](./moddate/) { get; set; } | Gets or sets the date of document modification. |
| [ModTimeZone](./modtimezone/) { get; set; } | Time zone of modification date. |
| [Producer](./producer/) { get; set; } | Gets or sets the document producer. |
| [Subject](./subject/) { get; set; } | Gets or sets the subject of the document. |
| [Title](./title/) { get; set; } | Gets or sets document title. |
| [Trapped](./trapped/) { get; set; } | Gets or sets the trapped flag. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(string, string) | Adds an element with the specified key and value into the collection. |
| [Clear](./clear/)() | Clears the document info. |
| [ClearCustomData](./clearcustomdata/)() | Clears custom data only, leaves all other predefined values (Title, Author, etc.). |
| static [IsPredefinedKey](./ispredefinedkey/)(string) | Determines if the key is predefined (Title, Author, etc.), not custom. |
| [Remove](./remove/)(string) | Removes the element with the specified key from the collection. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

