---
title: Aspose::Pdf::Comparison::SideBySideDocsComparisonResult class
linktitle: SideBySideDocsComparisonResult
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::SideBySideDocsComparisonResult class. Represents the class of the result of a side-by-side comparison operation performed on two documents in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.comparison/sidebysidedocscomparisonresult/
---
## SideBySideDocsComparisonResult class


Represents the class of the result of a side-by-side comparison operation performed on two documents.

```cpp
class SideBySideDocsComparisonResult : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_FirstDocChanges](./get_firstdocchanges/)() const | Get a list of changes to the pages of the first document. |
| [get_FullChanges](./get_fullchanges/)() const | Get a complete list of changes to the pages of the document. Each index in the list represents the two pages of the document that are being compared, and the list of change operations represents the list of changes to those pages. |
| [get_HasChanges](./get_haschanges/)() const | Gets the value indicates whether there are any changes between the compared documents. |
| [get_SecondDocChanges](./get_seconddocchanges/)() const | Get a list of changes to the pages of the second document. |
| [SideBySideDocsComparisonResult](./sidebysidedocscomparisonresult/)(bool, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<EditContainer\>\>\>\>\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Creates an instance of [SideBySideDocsComparisonResult](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
