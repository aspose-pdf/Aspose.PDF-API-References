---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengimpor semua data field dari aliran JSON ke dalam field dokumen yang mencocokkan field berdasarkan nama lengkapnya
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/form/importjson/
---
## Metode Form.ImportJson

Mengimpor semua data field dari aliran JSON ke dalam field dokumen, mencocokkan field berdasarkan nama lengkapnya.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputJsonStream | Stream | Aliran JSON input yang berisi data field yang akan diimpor ke dalam field dokumen. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)