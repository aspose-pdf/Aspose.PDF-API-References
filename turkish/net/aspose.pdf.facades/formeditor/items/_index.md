---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: FormEditor özelliği. Yeni oluşturulan liste kutusuna veya kombinasyon kutusuna eklenecek öğeleri ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.pdf.facades/formeditor/items/
---
## FormEditor.Items özelliği

Yeni oluşturulan liste kutusuna veya kombinasyon kutusuna eklenecek öğeleri ayarlar.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)