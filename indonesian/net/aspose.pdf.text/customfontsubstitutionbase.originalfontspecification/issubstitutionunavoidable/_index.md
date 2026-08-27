---
title: "CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti OriginalFontSpecification. Mendapatkan nilai yang menunjukkan bahwa substitusi tidak dapat dihindari."
type: docs
weight: 20
url: /id/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable property

Mengambil nilai yang menunjukkan bahwa substitusi tidak dapat dihindari.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Catatan

Mengembalikan true jika substitusi diminta karena tidak adanya font asli atau jika font asli tidak dapat digunakan dalam konteks suatu tugas. Jika pengguna mengabaikan flag dan tidak mengganti font - prosedur substitusi font default akan dijalankan. Namun hal ini memberikan kesempatan bagi pengguna untuk mengganti prosedur substitusi font standar dan menetapkan font yang lebih baik ke sistem. Mengembalikan false jika font asli hadir, valid, tetapi pengguna diizinkan untuk menggantinya.

### Lihat Juga

* class [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


