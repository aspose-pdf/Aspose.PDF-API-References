---
title: "FormEditor.ExportItems"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà FormEditor. Imposta le opzioni per la casella combinata con valori di esportazione."
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Imposta le opzioni per la casella combinata con valori di esportazione.

```csharp
public string[][] ExportItems { get; set; }
```

## Esempi

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

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


