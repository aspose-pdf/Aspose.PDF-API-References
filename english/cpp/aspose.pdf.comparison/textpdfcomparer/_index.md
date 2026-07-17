---
title: Aspose::Pdf::Comparison::TextPdfComparer class
linktitle: TextPdfComparer
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::TextPdfComparer class. Represents a class to comparison two PDF pages or PDF documents in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer class


Represents a class to comparison two PDF pages or PDF documents.

```cpp
class TextPdfComparer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [AssemblyDestinationPageText](./assemblydestinationpagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Restores changed text from the list of changes. |
| static [AssemblySourcePageText](./assemblysourcepagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Restores the original text from the list of changes. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compares two documents page by page. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Compares two documents page by page. The result is saved in a PDF file. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compares two documents page by page. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Compares two documents page by page. The result is saved in a PDF file. The documents are compared as a whole. Before comparing text, the texts of document pages are combined into one text. |
| static [ComparePages](./comparepages/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Compares document pages. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Gets comparison statistics. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Gets documents comparison statistics. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
