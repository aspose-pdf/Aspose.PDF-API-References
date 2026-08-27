---
title: "FormEditor.Items"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà FormEditor. Imposta gli elementi che saranno aggiunti a una nuova casella di riepilogo o combo box"
type: docs
weight: 50
url: /it/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

Imposta gli elementi che saranno aggiunti a una nuova casella di riepilogo o casella combinata.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


