---
title: "FormEditor.Items"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété FormEditor. Définit les éléments qui seront ajoutés à une liste ou à une boîte combinée nouvellement créée."
type: docs
weight: 50
url: /fr/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

Définit les éléments qui seront ajoutés à la liste ou à la zone combinée nouvellement créée.

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

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


