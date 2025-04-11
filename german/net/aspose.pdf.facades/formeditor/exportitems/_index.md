---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Eigenschaft. Legt Optionen für das Kombinationsfeld mit Exportwerten fest
type: docs
weight: 30
url: /de/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems-Eigenschaft

Legt Optionen für das Kombinationsfeld mit Exportwerten fest.

```csharp
public string[][] ExportItems { get; set; }
```

## Beispiele

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

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)