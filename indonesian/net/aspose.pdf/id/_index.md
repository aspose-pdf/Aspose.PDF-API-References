---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Id. Mewakili struktur pengidentifikasi file
type: docs
weight: 5850
url: /id/net/aspose.pdf/id/
---
## Kelas Id

Mewakili struktur pengidentifikasi file.

```csharp
public class Id
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Dimodifikasi](../../aspose.pdf/id/modified/) { get; } | Mengubah pengidentifikasi berdasarkan konten dokumen pada saat terakhir diperbarui. |
| [Asli](../../aspose.pdf/id/original/) { get; } | Pengidentifikasi permanen berdasarkan konten dokumen pada saat pertama kali dibuat. |

## Contoh

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)