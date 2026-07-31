---
title: "FormEditor.SetFieldAlignment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Mengatur gaya perataan dari field teks"
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Mengatur gaya perataan field teks.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |
| alignment | Int32 | Definisi gaya perataan, termasuk FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter, dan FormFieldFacade.AlignRight. |

### Nilai Kembalian

true jika field ditemukan dan perataan berhasil diatur.

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


