---
title: "FormEditor.Items"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية FormEditor. تعيين العناصر التي ستُضاف إلى صندوق قائمة أو مربع اختيار تم إنشاؤه حديثًا"
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

يضبط العناصر التي ستُضاف إلى صندوق القائمة أو صندوق القائمة المنسدلة الذي تم إنشاؤه حديثًا.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


