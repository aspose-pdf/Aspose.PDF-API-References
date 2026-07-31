---
title: "Form.GetField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengambil nilai bidang sesuai dengan nama bidangnya"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField method

Mendapatkan nilai bidang berdasarkan nama bidangnya.

```csharp
public string GetField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi kualifikasi. |

### Nilai Kembalian

Nilai bidang.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


