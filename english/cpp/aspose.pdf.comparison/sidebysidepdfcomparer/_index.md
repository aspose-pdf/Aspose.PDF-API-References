---
title: Aspose::Pdf::Comparison::SideBySidePdfComparer class
linktitle: SideBySidePdfComparer
second_title: Aspose.PDF for C++ API Reference
description: 'How to use Aspose::Pdf::Comparison::SideBySidePdfComparer class in C++.'
type: docs
weight: 1400
url: /cpp/aspose.pdf.comparison/sidebysidepdfcomparer/
---
## SideBySidePdfComparer class




```cpp
class SideBySidePdfComparer
```

## Methods

| Method | Description |
| --- | --- |
| static [Compare](./compare/)(System::SharedPtr\<Page\>, System::SharedPtr\<Page\>, System::String, System::SharedPtr\<SideBySideComparisonOptions\>) | Compares two pages. The result is saved in a PDF document in which the first page is written first, and then the second. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right. |
| static [Compare](./compare/)(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::String, System::SharedPtr\<SideBySideComparisonOptions\>) | Compares two documents. The pages are compared one by one. The pages of the compared documents are copied one after another into the resulting document. First the first page from the first document, then the first page from the second document. Next is the second one from the first document and then the second one from the second document, etc. You can open it in Adobe Acrobat in Two-page view to see the changes side by side. Deletions are noted on the page on the left, and insertions are noted on the page on the right. |
| [SideBySidePdfComparer](./sidebysidepdfcomparer/)() |  |
## See Also

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
