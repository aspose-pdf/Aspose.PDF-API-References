---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Properti OriginalFontSpecification. Mendapatkan nilai yang menunjukkan bahwa substitusi tidak dapat dihindari
type: docs
weight: 20
url: /id/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Properti CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Mendapatkan nilai yang menunjukkan bahwa substitusi tidak dapat dihindari.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Catatan

Mengembalikan true jika substitusi diminta karena ketidakhadiran font asli atau jika font asli tidak dapat digunakan dalam konteks tugas tertentu. Jika pengguna mengabaikan bendera dan tidak mengganti font - prosedur substitusi font default dilakukan. Namun, ini memberikan kesempatan bagi pengguna untuk mengganti prosedur substitusi font standar dan menetapkan font yang lebih baik ke sistem. Mengembalikan false jika font asli ada, valid, tetapi diperbolehkan bagi pengguna untuk menggantinya.

### Lihat Juga

* kelas [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)