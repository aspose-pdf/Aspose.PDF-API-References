---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur gaya perataan dari sebuah field teks
type: docs
weight: 260
url: /id/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## Metode FormEditor.SetFieldAlignment

Atur gaya perataan dari sebuah field teks.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang memenuhi syarat. |
| alignment | Int32 | Definisi gaya perataan, termasuk FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter dan FormFieldFacade.AlignRight. |

### Nilai Kembali

true jika field ditemukan dan perataan telah diatur.

## Contoh

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)