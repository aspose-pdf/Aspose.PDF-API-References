---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Свойство FormEditor. Устанавливает элементы, которые будут добавлены в только что созданный список или комбинированный ящик
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/formeditor/items/
---
## Свойство FormEditor.Items

Устанавливает элементы, которые будут добавлены в только что созданный список или комбинированный ящик.

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

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)