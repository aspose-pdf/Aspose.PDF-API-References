---
title: Class StructureRecognitionVisitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Flow.StructureRecognitionVisitor class. Base class for a custom document structure recognition visitor
type: docs
weight: 5050
url: /net/aspose.pdf.flow/structurerecognitionvisitor/
---
## StructureRecognitionVisitor class

Base class for a custom document structure recognition visitor

```csharp
public class StructureRecognitionVisitor : IStructureRecognitionVisitor
```

## Constructors

| Name | Description |
| --- | --- |
| [StructureRecognitionVisitor](structurerecognitionvisitor/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| virtual [EndDocument](../../aspose.pdf.flow/structurerecognitionvisitor/enddocument/)() | Signals the end of document processing. |
| virtual [Recognize](../../aspose.pdf.flow/structurerecognitionvisitor/recognize/#recognize)(Document) | Start recognition of document |
| virtual [Recognize](../../aspose.pdf.flow/structurerecognitionvisitor/recognize/#recognize_1)(Page) | Start recognition of page |
| virtual [StartDocument](../../aspose.pdf.flow/structurerecognitionvisitor/startdocument/)() | Called when the document traversal starts. |
| virtual [VisitParagraph](../../aspose.pdf.flow/structurerecognitionvisitor/visitparagraph/)(BaseParagraph) | Called when a paragraph node is visited. |
| virtual [VisitSectionEnd](../../aspose.pdf.flow/structurerecognitionvisitor/visitsectionend/)(MarginInfo) | Visits the end of a recognized section in the document. |
| virtual [VisitTable](../../aspose.pdf.flow/structurerecognitionvisitor/visittable/)(Table) | Visits a recognized table in the document structure. |

### See Also

* interface [IStructureRecognitionVisitor](../istructurerecognitionvisitor/)
* namespace [Aspose.Pdf.Flow](../../aspose.pdf.flow/)
* assembly [Aspose.PDF](../../)


