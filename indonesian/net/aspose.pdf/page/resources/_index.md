---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: Properti Halaman. Mendapatkan sumber daya halaman. Objek Sumber Daya berisi koleksi gambar, formulir, dan font. Sumber Daya
type: docs
weight: 240
url: /id/net/aspose.pdf/page/resources/
---
## Properti Page.Resources

Mendapatkan sumber daya halaman. Objek Sumber Daya berisi koleksi gambar, formulir, dan font. `Resources`

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

* kelas [Resources](../../resources/)
* kelas [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)