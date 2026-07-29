---
title: "Document.Actions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية Document. تحصل على إجراءات المستند. هذه الخاصية هي مثال من فئة DocumentActions التي تسمح بالحصول/التعيين لإجراءات BeforClosing و BeforSaving وغيرها."
type: docs
weight: 30
url: /ar/net/aspose.pdf/document/actions/
---
## Document.Actions property

يحصل على إجراءات المستند. هذه الخاصية هي نسخة من الفئة DocumentActions التي تسمح بالحصول/تعيين إجراءات BeforClosing، BeforSaving، إلخ.

```csharp
public DocumentActionCollection Actions { get; }
```

## أمثلة

يوضح هذا المثال كيفية الحصول على إجراء ما بعد الفتح للمستند:

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


