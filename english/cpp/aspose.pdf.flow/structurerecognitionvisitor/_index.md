---
title: Aspose::Pdf::Flow::StructureRecognitionVisitor class
linktitle: StructureRecognitionVisitor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Flow::StructureRecognitionVisitor class. Base class for a custom document structure recognition visitor in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class


Base class for a custom document structure recognition visitor.

```cpp
class StructureRecognitionVisitor : public Aspose::Pdf::Flow::IStructureRecognitionVisitor
```

## Methods

| Method | Description |
| --- | --- |
| [EndDocument](./enddocument/)() override | Signals the end of document processing. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Document\>) | Start recognition of document. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Page\>) | Start recognition of page. |
| [StartDocument](./startdocument/)() override | Called when the document traversal starts. |
| [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) override | Called when a paragraph node is visited. |
| [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) override | Visits the end of a recognized section in the document. |
| [VisitTable](./visittable/)(System::SharedPtr\<Table\>) override | Visits a recognized table in the document structure. |
## See Also

* Class [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
