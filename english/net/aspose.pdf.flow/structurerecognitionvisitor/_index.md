---
title: "StructureRecognitionVisitor Class"
linktitle: "StructureRecognitionVisitor"
articleTitle: "StructureRecognitionVisitor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Flow.StructureRecognitionVisitor class. Base class for a custom document structure recognition visitor"
type: docs
weight: 30
url: "/net/aspose.pdf.flow/structurerecognitionvisitor/"
keywords: "StructureRecognitionVisitor, Aspose.Pdf.Flow, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## StructureRecognitionVisitor class

Base class for a custom document structure recognition visitor

```csharp
public class StructureRecognitionVisitor : IStructureRecognitionVisitor
```

## Constructors

| Name | Description |
| --- | --- |
| [StructureRecognitionVisitor](./structurerecognitionvisitor/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| virtual [EndDocument](./enddocument/)() | Signals the end of document processing. |
| virtual [Recognize](./recognize/)(Document) | Start recognition of document |
| virtual [Recognize](./recognize/)(Page) | Start recognition of page |
| virtual [StartDocument](./startdocument/)() | Called when the document traversal starts. |
| virtual [VisitParagraph](./visitparagraph/)(BaseParagraph) | Called when a paragraph node is visited. |
| virtual [VisitSectionEnd](./visitsectionend/)(MarginInfo) | Visits the end of a recognized section in the document. |
| virtual [VisitTable](./visittable/)(Table) | Visits a recognized table in the document structure. |

### See Also

* namespace [Aspose.Pdf.Flow](../../aspose.pdf.flow/)
* assembly [Aspose.PDF](../../)

