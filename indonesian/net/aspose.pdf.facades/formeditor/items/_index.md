---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Properti FormEditor. Mengatur item yang akan ditambahkan ke kotak daftar atau kotak kombo yang baru dibuat
type: docs
weight: 50
url: /id/net/aspose.pdf.facades/formeditor/items/
---
## Properti FormEditor.Items

Mengatur item yang akan ditambahkan ke kotak daftar atau kotak kombo yang baru dibuat.

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

* kelas [FormEditor](../)
* ruang nama [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)