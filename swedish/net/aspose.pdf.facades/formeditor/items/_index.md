---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-egenskap. Ställer in objekt som kommer att läggas till i den nyss skapade listboxen eller kombinationsrutan
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items-egenskap

Ställer in objekt som kommer att läggas till i den nyss skapade listboxen eller kombinationsrutan.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)