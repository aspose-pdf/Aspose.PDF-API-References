---
title: Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges method
linktitle: get_FullChanges
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges method. Get a complete list of changes to the pages of the document. Each index in the list represents the two pages of the document that are being compared, and the list of change operations represents the list of changes to those pages in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/get_fullchanges/
---
## SideBySideDocsComparisonResult::get_FullChanges method


Get a complete list of changes to the pages of the document. Each index in the list represents the two pages of the document that are being compared, and the list of change operations represents the list of changes to those pages.

```cpp
const System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<System::Collections::Generic::List<System::SharedPtr<DiffOperation>>>>> & Aspose::Pdf::Comparison::SideBySideDocsComparisonResult::get_FullChanges() const
```

## Remarks


The list does not contain information about the position of changes on the pages but shows the full cross-pages changes.

> 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [DiffOperation](../../diffoperation/)
* Class [SideBySideDocsComparisonResult](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
