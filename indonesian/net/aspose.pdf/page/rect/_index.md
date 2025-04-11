---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: Properti Halaman. Mengambil atau mengatur persegi panjang halaman. Untuk mendapatkan: kotak pemotongan halaman dikembalikan jika ditentukan, jika tidak, kotak media halaman dikembalikan. Untuk mengatur: kotak media halaman selalu diatur. Harap dicatat bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, silakan gunakan ActualRect
type: docs
weight: 230
url: /id/net/aspose.pdf/page/rect/
---
## Properti Page.Rect

Mengambil atau mengatur persegi panjang halaman. Untuk mendapatkan: kotak pemotongan halaman dikembalikan jika ditentukan, jika tidak, kotak media halaman dikembalikan. Untuk mengatur: kotak media halaman selalu diatur. Harap dicatat bahwa properti ini tidak mempertimbangkan rotasi halaman. Untuk mendapatkan persegi panjang halaman dengan mempertimbangkan rotasi, silakan gunakan ActualRect.

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

* kelas [Rectangle](../../rectangle/)
* kelas [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)