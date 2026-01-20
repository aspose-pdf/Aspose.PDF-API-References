---
title: Aspose::Pdf::Flow::IStructureRecognitionVisitor class
linktitle: IStructureRecognitionVisitor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Flow::IStructureRecognitionVisitor class. Base interface for a custom document structure recognition visitor in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.flow/istructurerecognitionvisitor/
---
## IStructureRecognitionVisitor class


Base interface for a custom document structure recognition visitor.

```cpp
class IStructureRecognitionVisitor : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Signals the end of document processing. |
| virtual [StartDocument](./startdocument/)() | Called when the document traversal starts. |
| virtual [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) | Called when a paragraph node is visited. |
| virtual [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) | Visits the end of a recognized section in the document. |
| virtual [VisitTable](./visittable/)(System::SharedPtr\<Table\>) | Visits a recognized table in the document structure. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
