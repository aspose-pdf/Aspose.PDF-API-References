---
title: ExportItems
second_title: Aspose.PDF для справочника API .NET
description: Устанавливает параметры для поля со списком с экспортируемыми значениями.
type: docs
weight: 50
url: /ru/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Устанавливает параметры для поля со списком с экспортируемыми значениями.

```csharp
public string[][] ExportItems { get; set; }
```

### Примеры

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

### Смотрите также

* class [FormEditor](../../formeditor)
* пространство имен [Aspose.Pdf.Facades](../../formeditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->