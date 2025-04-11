---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Properti halaman. Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik bahwa halaman akan ditampilkan selama presentasi. Mengembalikan 1 jika durasi tidak didefinisikan
type: docs
weight: 110
url: /id/net/aspose.pdf/page/duration/
---
## Properti Page.Duration

Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik bahwa halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan.

```csharp
public double Duration { get; set; }
```

## Contoh

Contoh menunjukkan cara mendapatkan durasi halaman

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### Lihat Juga

* kelas [Page](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)