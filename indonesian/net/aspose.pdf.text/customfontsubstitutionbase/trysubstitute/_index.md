---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Metode CustomFontSubstitutionBase. Mengganti font asli dengan font lain
type: docs
weight: 20
url: /id/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Metode CustomFontSubstitutionBase.TrySubstitute

Mengganti font asli dengan font lain.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Spesifikasi font asli. |
| substitutionFont | Font& | Font pengganti. |

### Nilai Kembali

True jika penggantian berhasil.

## Catatan

Kelas CustomFontSubstitutionBase harus diwarisi untuk mengimplementasikan logika penggantian font kustom. Metode TrySubstitute harus dioverride dengan benar: Harus mengembalikan true jika penggantian diperlukan. substitutionFont harus diatur ke objek Font yang valid. Harus mengembalikan false jika tidak ada penggantian yang diperlukan. substitutionFont dapat diatur ke null.

### Lihat Juga

* kelas [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* kelas [Font](../../font/)
* kelas [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)