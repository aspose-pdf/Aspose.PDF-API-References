---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengimpor konten dari field dari file xfdfxml dan menempatkannya ke dalam pdf baru
type: docs
weight: 300
url: /id/net/aspose.pdf.facades/form/importxfdf/
---
## Metode Form.ImportXfdf

Mengimpor konten dari field dari file xfdf(xml) dan menempatkannya ke dalam pdf baru.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputXfdfStream | Stream | Aliran xfdf(xml) input. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)