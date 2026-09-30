---
title: "PageCollectionExtensions Class"
linktitle: "PageCollectionExtensions"
articleTitle: "PageCollectionExtensions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PageCollectionExtensions class. Represents the extension method for updating header and footer pagination."
type: docs
weight: 2110
url: "/net/aspose.pdf/pagecollectionextensions/"
keywords: "PageCollectionExtensions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PageCollectionExtensions class

Represents the extension method for updating header and footer pagination.

```csharp
public static class PageCollectionExtensions
```

## Methods

| Name | Description |
| --- | --- |
| static [AddBatesNumbering](./addbatesnumbering/)(this PageCollection, Action<BatesNArtifact>) | Adds Bates numbering to each page in the given page collection using the specified action to configure the BatesNArtifact. |
| static [AddBatesNumbering](./addbatesnumbering/)(this PageCollection, BatesNArtifact) | Adds the specified Bates numbering artifact to each page in the given page collection. |
| static [AddPagination](./addpagination/)(this PageCollection, List<PaginationArtifact>) | Adds the specified pagination artifacts to each page in the given page collection. |
| static [DeleteBatesNumbering](./deletebatesnumbering/)(this PageCollection) | Deletes all Bates numbering artifacts from each page in the given page collection. |
| static [UpdatePagination](./updatepagination/)(this PageCollection) | Updates the header and footer page numbers and dates for all pages. This will work if the document has at least one pagination artifact with special settings data. All pages in the collection will be updated with the source artifact according to its settings. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

