---
title: "XFA.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية XFA. تحصل أو تعيين قيمة عقدة البيانات وفقًا للمسار"
type: docs
weight: 50
url: /ar/net/aspose.pdf.forms/xfa/item/
---
## XFA indexer

يحصل أو يعيّن قيمة عقدة البيانات وفق *المسار*.

```csharp
public string this[string path] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| المسار | مسار عقدة البيانات، مثال: form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. تأكد من تضمين الفهارس حتى إذا كانت البيانات تحتوي على حدوث واحد فقط لكل عقدة، أي اكتب node1[0].node2[0]... بدلاً من node1.node2... |

### قيمة الإرجاع

قيمة عقدة البيانات.

### انظر أيضًا

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


