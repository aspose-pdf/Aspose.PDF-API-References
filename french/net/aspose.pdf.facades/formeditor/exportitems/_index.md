---
title: "FormEditor.ExportItems"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété FormEditor. Définit les options pour la liste déroulante avec les valeurs d'exportation."
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/formeditor/exportitems/
---
## FormEditor.ExportItems property

Définit les options pour la zone combinée avec des valeurs d'exportation.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


