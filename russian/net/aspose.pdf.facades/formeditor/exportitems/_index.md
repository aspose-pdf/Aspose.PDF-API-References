---
title: "FormEditor.ExportItems"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство FormEditor. Устанавливает параметры для комбобокса с экспортируемыми значениями"
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Устанавливает параметры для комбобокса с экспортными значениями.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


