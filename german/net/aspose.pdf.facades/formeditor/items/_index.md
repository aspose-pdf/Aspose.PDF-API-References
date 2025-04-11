---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Eigenschaft. Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden.
type: docs
weight: 50
url: /de/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items-Eigenschaft

Legt Elemente fest, die zu einer neu erstellten Listbox oder Kombobox hinzugefügt werden.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)