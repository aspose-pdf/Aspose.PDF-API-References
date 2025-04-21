---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: Properti dokumen. Mengambil atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. Ketika halaman dari dokumen sumber disalin ke dokumen tujuan, proses penyalinan dihentikan dengan pengecualian jika beberapa objek dalam file sumber rusak ketika flag ini false. Secara default true
type: docs
weight: 270
url: /id/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Properti Document.IgnoreCorruptedObjects

Mengambil atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. Ketika halaman dari dokumen sumber disalin ke dokumen tujuan, proses penyalinan dihentikan dengan pengecualian jika beberapa objek dalam file sumber rusak ketika flag ini false. contoh: dest.Pages.Add(src.Pages); Jika flag ini diatur ke true maka objek yang rusak akan diganti dengan nilai kosong. Secara default: true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Lihat Juga

* kelas [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)