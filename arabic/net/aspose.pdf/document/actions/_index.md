---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: خاصية الوثيقة. تحصل على إجراءات الوثيقة. هذه الخاصية هي مثيل لفئة DocumentActions التي تسمح بالحصول على/تعيين إجراءات BeforClosing و BeforSaving وغيرها.
type: docs
weight: 30
url: /ar/net/aspose.pdf/document/actions/
---
## خاصية Document.Actions

تحصل على إجراءات الوثيقة. هذه الخاصية هي مثيل لفئة DocumentActions التي تسمح بالحصول على/تعيين إجراءات BeforClosing و BeforSaving وغيرها.

```csharp
public DocumentActionCollection Actions { get; }
```

## أمثلة

هذا المثال يوضح كيفية الحصول على إجراء بعد فتح الوثيقة:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### انظر أيضًا

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)