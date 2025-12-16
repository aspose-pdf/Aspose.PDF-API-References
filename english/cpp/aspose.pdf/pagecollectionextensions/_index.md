---
title: Aspose::Pdf::PageCollectionExtensions class
linktitle: PageCollectionExtensions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PageCollectionExtensions class. Represents the extension method for updating header and footer pagination in C++.'
type: docs
weight: 13500
url: /cpp/aspose.pdf/pagecollectionextensions/
---
## PageCollectionExtensions class


Represents the extension method for updating header and footer pagination.

```cpp
class PageCollectionExtensions
```

## Methods

| Method | Description |
| --- | --- |
| static [AddBatesNumbering](./addbatesnumbering/)(System::SharedPtr\<PageCollection\>, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) | Adds Bates numbering to each page in the given page collection using the specified action to configure the [BatesNArtifact](../batesnartifact/). |
| static [AddBatesNumbering](./addbatesnumbering/)(System::SharedPtr\<PageCollection\>, System::SharedPtr\<BatesNArtifact\>) | Adds the specified Bates numbering artifact to each page in the given page collection. |
| static [AddPagination](./addpagination/)(System::SharedPtr\<PageCollection\>, System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<PaginationArtifact\>\>\>) | Adds the specified pagination artifacts to each page in the given page collection. |
| static [DeleteBatesNumbering](./deletebatesnumbering/)(System::SharedPtr\<PageCollection\>) | Deletes all Bates numbering artifacts from each page in the given page collection. |
| [PageCollectionExtensions](./pagecollectionextensions/)() |  |
| static [UpdatePagination](./updatepagination/)(System::SharedPtr\<PageCollection\>) | Updates the header and footer page numbers and dates for all pages. This will work if the document has at least one pagination artifact with special settings data. All pages in the collection will be updated with the source artifact according to its settings. |
## See Also

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
