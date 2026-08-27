---
title: "FormEditor.Items"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство FormEditor. Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс"
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

Устанавливает элементы, которые будут добавлены в только что созданный список или комбобокс.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### См. также

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


