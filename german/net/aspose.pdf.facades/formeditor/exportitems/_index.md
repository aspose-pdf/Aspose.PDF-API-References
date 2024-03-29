---
title: ExportItems
second_title: Aspose.PDF für .NET-API-Referenz
description: Legt Optionen für das Kombinationsfeld mit Exportwerten fest.
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Legt Optionen für das Kombinationsfeld mit Exportwerten fest.

```csharp
public string[][] ExportItems { get; set; }
```

### Beispiele

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

### Siehe auch

* class [FormEditor](../../formeditor)
* namensraum [Aspose.Pdf.Facades](../../formeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
