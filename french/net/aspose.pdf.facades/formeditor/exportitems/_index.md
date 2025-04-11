---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Définit les options pour la boîte combinée avec des valeurs d'exportation
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/formeditor/exportitems/
---
## Propriété FormEditor.ExportItems

Définit les options pour la boîte combinée avec des valeurs d'exportation.

```csharp
public string[][] ExportItems { get; set; }
```

## Exemples

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

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)