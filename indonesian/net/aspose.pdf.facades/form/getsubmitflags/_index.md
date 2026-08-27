---
title: "Form.GetSubmitFlags"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengembalikan flag pengiriman tombol submit"
type: docs
weight: 270
url: /id/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Mengembalikan flag pengiriman tombol submit

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |

### Nilai Kembalian

Flag pengiriman tombol.

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


