---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: خاصية FormEditor. تعيين العناصر التي ستضاف إلى مربع القائمة أو مربع التحرير المنسدل الذي تم إنشاؤه حديثًا
type: docs
weight: 50
url: /ar/net/aspose.pdf.facades/formeditor/items/
---
## خاصية FormEditor.Items

تعيين العناصر التي ستضاف إلى مربع القائمة أو مربع التحرير المنسدل الذي تم إنشاؤه حديثًا.

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