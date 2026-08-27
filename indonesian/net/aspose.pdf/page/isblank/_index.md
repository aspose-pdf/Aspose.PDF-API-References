---
title: "Page.IsBlank"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Page. Mendapatkan flag apakah halaman kosong atau tidak"
type: docs
weight: 490
url: /id/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Mendapatkan flag apakah halaman kosong atau tidak.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillThresholdFactor | Double | Nilai ambang pengisian yang mengatur sensitivitas deteksi. Harus berada dalam rentang [0..1). |

### Nilai Kembalian

True - jika halaman kosong; jika tidak, false.

## Catatan

Untuk menentukan apakah sebuah halaman kosong atau tidak, rasio ruang terisi terhadap total ruang halaman dihitung. Rasio ini dibandingkan dengan parameter fillThresholdFactor dan jika lebih kecil, halaman dianggap kosong.

### Lihat Juga

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


