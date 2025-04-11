---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur gaya perataan vertikal dari sebuah field teks
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## Metode FormEditor.SetFieldAlignmentV

Atur gaya perataan vertikal dari sebuah field teks.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang memenuhi syarat. |
| alignment | Int32 | Definisi gaya perataan, termasuk FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle dan FormFieldFacade.AlignRight. |

### Nilai Kembali

true jika field ditemukan dan perataan berhasil diisi.

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)