---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Propriété FormEditor. Définit les éléments qui seront ajoutés à une nouvelle liste déroulante ou boîte combinée
type: docs
weight: 50
url: /fr/net/aspose.pdf.facades/formeditor/items/
---
## Propriété FormEditor.Items

Définit les éléments qui seront ajoutés à une nouvelle liste déroulante ou boîte combinée.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)