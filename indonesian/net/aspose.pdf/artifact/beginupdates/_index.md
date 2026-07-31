---
title: "Artifact.BeginUpdates"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Artifact. Memulai pembaruan tertunda. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. Biasanya operator artefak berubah kapan saja ketika properti artefak diubah. Hal ini menyebabkan perubahan konten halaman setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates. Ini memungkinkan mengubah konten halaman hanya sekali."
type: docs
weight: 230
url: /id/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

Mulai pembaruan tertunda. Gunakan fitur ini jika Anda perlu melakukan beberapa perubahan pada artefak yang sama untuk meningkatkan kinerja. Biasanya operator artefak diubah kapan saja ketika properti artefak diubah. Hal ini menyebabkan perubahan isi halaman setiap kali artefak diubah. Untuk menghindari efek ini, letakkan semua pembaruan artefak di antara panggilan StartUpdates/SaveUpdates. Ini memungkinkan mengubah isi halaman hanya sekali.

```csharp
public void BeginUpdates()
```

## Contoh

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Lihat Juga

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


