---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: خاصية FormEditor. تعيين خيارات لعنصر القائمة المنسدلة مع قيم التصدير
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/formeditor/exportitems/
---
## خاصية FormEditor.ExportItems

تعيين خيارات لعنصر القائمة المنسدلة مع قيم التصدير.

```csharp
public string[][] ExportItems { get; set; }
```

## أمثلة

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

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)