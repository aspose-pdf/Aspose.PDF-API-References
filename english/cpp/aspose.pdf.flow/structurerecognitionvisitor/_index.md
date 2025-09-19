---
title: Aspose::Pdf::Flow::StructureRecognitionVisitor class
linktitle: StructureRecognitionVisitor
second_title: Aspose.PDF for C++ API Reference
description: 'How to use Aspose::Pdf::Flow::StructureRecognitionVisitor class in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class




```cpp
class StructureRecognitionVisitor : public Aspose::Pdf::Flow::IStructureRecognitionVisitor
```

## Methods

| Method | Description |
| --- | --- |
| [EndDocument](./enddocument/)() override | Signals the end of document processing. |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Document\>) |  |
| virtual [Recognize](./recognize/)(System::SharedPtr\<Page\>) |  |
| [StartDocument](./startdocument/)() override | Signals the start of document processing. |
| [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) override | Visits a recognized paragraph in the document structure. |
| [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) override | Visits the end of a recognized section in the document. |
| [VisitTable](./visittable/)(System::SharedPtr\<Table\>) override | Visits a recognized table in the document structure. |
## See Also

* Class [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
