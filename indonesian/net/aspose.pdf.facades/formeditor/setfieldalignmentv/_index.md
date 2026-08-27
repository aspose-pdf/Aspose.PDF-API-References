---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Atur gaya perataan vertikal bidang teks."
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Mengatur gaya perataan vertikal field teks.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |
| alignment | Int32 | Definisi gaya perataan, termasuk FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle, dan FormFieldFacade.AlignRight. |

### Nilai Kembalian

true jika bidang ditemukan dan perataan berhasil diterapkan.

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


