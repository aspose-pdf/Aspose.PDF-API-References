---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: FormEditor özelliği. Dışa aktarma değerleri ile combo kutusu için seçenekleri ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems özelliği

Dışa aktarma değerleri ile combo kutusu için seçenekleri ayarlar.

```csharp
public string[][] ExportItems { get; set; }
```

## Örnekler

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

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)