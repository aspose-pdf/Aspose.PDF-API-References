---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengembalikan bendera pengiriman tombol submit
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/form/getsubmitflags/
---
## Metode Form.GetSubmitFlags

Mengembalikan bendera pengiriman tombol submit

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang memenuhi syarat. |

### Nilai Kembali

Bendera pengiriman dari tombol.

## Contoh

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Lihat Juga

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)