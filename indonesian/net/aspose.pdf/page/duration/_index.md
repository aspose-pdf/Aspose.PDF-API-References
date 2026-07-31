---
title: "Page.Duration"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Page. Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan 1 jika durasi tidak didefinisikan."
type: docs
weight: 110
url: /id/net/aspose.pdf/page/duration/
---
## Page.Duration property

Mendapatkan atau mengatur durasi tampilan halaman. Ini adalah waktu dalam detik yang halaman akan ditampilkan selama presentasi. Mengembalikan -1 jika durasi tidak didefinisikan.

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

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


