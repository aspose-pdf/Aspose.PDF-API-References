---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Properti dokumen. Mendapatkan atau mengatur koleksi halaman dokumen. Perhatikan bahwa halaman diberi nomor mulai dari 1 dalam koleksi
type: docs
weight: 470
url: /id/net/aspose.pdf/document/pages/
---
## Properti Document.Pages

Mendapatkan atau mengatur koleksi halaman dokumen. Perhatikan bahwa halaman diberi nomor mulai dari 1 dalam koleksi.

```csharp
public PageCollection Pages { get; }
```

## Contoh

Contoh di bawah ini menunjukkan cara beroperasi dengan halaman dokumen: Cara untuk mendapatkan jumlah halaman dan cara untuk mendapatkan persegi panjang halaman awal dokumen.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Lihat Juga

* kelas [PageCollection](../../pagecollection/)
* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)