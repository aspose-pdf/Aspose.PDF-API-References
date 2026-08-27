---
title: "FormEditor.ExportItems"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti FormEditor. Mengatur opsi untuk kotak kombo dengan nilai ekspor"
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Mengatur opsi untuk combo box dengan nilai ekspor.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


