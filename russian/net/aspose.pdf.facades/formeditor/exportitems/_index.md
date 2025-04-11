---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: Свойство FormEditor. Устанавливает параметры для комбинированного поля с экспортируемыми значениями
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/formeditor/exportitems/
---
## Свойство FormEditor.ExportItems

Устанавливает параметры для комбинированного поля с экспортируемыми значениями.

```csharp
public string[][] ExportItems { get; set; }
```

## Примеры

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### См. также

* класс [FormEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)