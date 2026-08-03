---
title: "FormEditor.ExportItems"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-egenskap. Ställer in alternativ för kombinationsruta med exportvärden"
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Ställer in alternativ för kombinationsruta med exportvärden.

```csharp
public string[][] ExportItems { get; set; }
```

## Exempel

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

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


