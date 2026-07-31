---
title: "Document.Pages"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Document. Mendapatkan atau mengatur koleksi halaman dokumen. Catatan bahwa halaman diberi nomor mulai dari 1 dalam koleksi"
type: docs
weight: 490
url: /id/net/aspose.pdf/document/pages/
---
## Document.Pages property

Mendapatkan atau mengatur koleksi halaman dokumen. Perhatikan bahwa halaman diberi nomor mulai dari 1 dalam koleksi.

```csharp
public PageCollection Pages { get; }
```

## Contoh

Contoh di bawah ini menunjukkan cara beroperasi dengan halaman dokumen: Cara mendapatkan jumlah halaman dan cara mendapatkan persegi panjang halaman pertama dokumen.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Lihat Juga

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


