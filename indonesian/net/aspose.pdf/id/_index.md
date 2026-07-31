---
title: "Kelas Id"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Id. Mewakili struktur pengidentifikasi file"
type: docs
weight: 5980
url: /id/net/aspose.pdf/id/
---
## Id class

Mewakili struktur pengidentifikasi file.

```csharp
public class Id
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Mengubah pengidentifikasi berdasarkan isi dokumen pada saat terakhir diperbarui. |
| [Original](../../aspose.pdf/id/original/) { get; } | Pengidentifikasi permanen berdasarkan isi dokumen pada saat dokumen tersebut pertama kali dibuat. |

## Contoh

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


