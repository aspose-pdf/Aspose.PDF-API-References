---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode CustomFontSubstitutionBase. Mengganti font asli dengan font lain."
type: docs
weight: 20
url: /id/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Mengganti font asli dengan font lain.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Spesifikasi font asli. |
| substitutionFont | Font& | Font substitusi. |

### Nilai Kembalian

True jika substitusi berhasil.

## Catatan

Kelas CustomFontSubstitutionBase harus diwarisi untuk menerapkan logika substitusi font khusus. Metode TrySubstitute harus dioverride dengan benar: Harus mengembalikan true jika substitusi diperlukan. substitutionFont harus diatur ke objek Font yang valid. Harus mengembalikan false jika tidak diperlukan substitusi. substitutionFont dapat diatur ke null.

### Lihat Juga

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


