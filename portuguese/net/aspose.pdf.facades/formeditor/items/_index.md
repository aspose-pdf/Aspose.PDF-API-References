---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Propriedade FormEditor. Define os itens que serão adicionados a uma caixa de lista ou caixa de combinação recém-criada
type: docs
weight: 50
url: /pt/net/aspose.pdf.facades/formeditor/items/
---
## Propriedade FormEditor.Items

Define os itens que serão adicionados a uma caixa de lista ou caixa de combinação recém-criada.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)