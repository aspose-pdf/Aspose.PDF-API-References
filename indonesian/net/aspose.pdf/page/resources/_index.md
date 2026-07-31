---
title: "Page.Resources"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Page. Mendapatkan sumber daya halaman. Objek Resources berisi koleksi gambar, formulir, dan font. Resources"
type: docs
weight: 240
url: /id/net/aspose.pdf/page/resources/
---
## Page.Resources property

Mendapatkan sumber daya halaman. Objek Resources berisi koleksi gambar, formulir, dan font. `Resources`

```csharp
public Resources Resources { get; }
```

## Contoh

Contoh menunjukkan pemindaian melalui gambar halaman:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### Lihat Juga

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


