---
title: "FormEditor.Items"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor egenskap. Anger objekt som kommer att läggas till i en ny skapad list box eller combo box"
type: docs
weight: 50
url: /sv/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


