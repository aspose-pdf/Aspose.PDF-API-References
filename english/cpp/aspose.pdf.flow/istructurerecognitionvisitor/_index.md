---
title: Aspose::Pdf::Flow::IStructureRecognitionVisitor class
linktitle: IStructureRecognitionVisitor
second_title: Aspose.PDF for C++ API Reference
description: 'How to use Aspose::Pdf::Flow::IStructureRecognitionVisitor class in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.flow/istructurerecognitionvisitor/
---
## IStructureRecognitionVisitor class




```cpp
class IStructureRecognitionVisitor : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Signals the end of document processing. |
| virtual [StartDocument](./startdocument/)() | Signals the start of document processing. |
| virtual [VisitParagraph](./visitparagraph/)(System::SharedPtr\<BaseParagraph\>) | Visits a recognized paragraph in the document structure. |
| virtual [VisitSectionEnd](./visitsectionend/)(System::SharedPtr\<MarginInfo\>) | Visits the end of a recognized section in the document. |
| virtual [VisitTable](./visittable/)(System::SharedPtr\<Table\>) | Visits a recognized table in the document structure. |
## Remarks


Base interface for a custom document structure recognition visitor 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Flow](../)
* Library [Aspose.PDF for C++](../../)
