---
title: "Form.ImportXfdf"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengimpor konten bidang dari file xfdfxml dan menempatkannya ke PDF baru."
type: docs
weight: 300
url: /id/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Mengimpor konten bidang dari file xfdf(xml) dan menaruhnya ke dalam pdf baru.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputXfdfStream | Stream | Aliran xfdf(xml) masukan. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


