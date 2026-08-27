---
title: "FormEditor.Items"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti FormEditor. Mengatur item yang akan ditambahkan ke list box atau combo box yang baru dibuat"
type: docs
weight: 50
url: /id/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items property

Mengatur item yang akan ditambahkan ke list box atau combo box yang baru dibuat.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


