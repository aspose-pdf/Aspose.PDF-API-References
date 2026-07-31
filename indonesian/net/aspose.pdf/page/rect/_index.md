---
title: "Page.Rect"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Page. Mendapatkan atau mengatur persegi panjang halaman. Untuk mendapatkan, kotak potong halaman dikembalikan jika ditentukan, jika tidak kotak media halaman yang dikembalikan. Untuk mengatur, kotak media halaman selalu diatur. Harap perhatikan bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, gunakan ActualRect."
type: docs
weight: 230
url: /id/net/aspose.pdf/page/rect/
---
## Page.Rect property

Mendapatkan atau mengatur persegi panjang halaman. Untuk mendapatkan: crop box halaman dikembalikan jika ditentukan, jika tidak crop box media halaman yang dikembalikan. Untuk mengatur: media box halaman selalu diatur. Harap perhatikan bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, gunakan ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Contoh

Contoh menunjukkan cara mendapatkan persegi panjang halaman:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Lihat Juga

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


