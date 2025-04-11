---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: Properti FormEditor. Mengatur opsi untuk kotak kombo dengan nilai ekspor
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/formeditor/exportitems/
---
## Properti FormEditor.ExportItems

Mengatur opsi untuk kotak kombo dengan nilai ekspor.

```csharp
public string[][] ExportItems { get; set; }
```

## Contoh

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

### Lihat Juga

* kelas [FormEditor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)