---
title: "XImage.TrySetAlternativeText"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode XImage. Menetapkan teks alternatif untuk XImage pada halaman"
type: docs
weight: 180
url: /id/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Menetapkan teks alternatif untuk sebuah XImage pada halaman.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alternativeText | String | Teks alternatif yang harus ditentukan. |
| halaman | Halaman | Halaman tempat XImage berada. |

### Nilai Kembalian

Benar jika alternativeText untuk XImage telah diatur. Salah jika alternativeText untuk XImage tidak diatur.

## Catatan

Metode mengembalikan false dalam kasus berikut: - XImage tidak ditemukan pada halaman yang ditentukan. - XImage muncul beberapa kali pada halaman dengan elemen struktural yang berbeda, sehingga tidak jelas instansi mana yang harus menerima teks alternatif.

### Lihat Juga

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


