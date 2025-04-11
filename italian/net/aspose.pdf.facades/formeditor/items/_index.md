---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Proprietà FormEditor. Imposta gli elementi che verranno aggiunti a una nuova casella di elenco o a un menu a discesa
type: docs
weight: 50
url: /it/net/aspose.pdf.facades/formeditor/items/
---
## Proprietà FormEditor.Items

Imposta gli elementi che verranno aggiunti a una nuova casella di elenco o a un menu a discesa.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)