---
title: "Form.ImportJson"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengimpor semua data bidang dari aliran JSON ke bidang dokumen yang cocok dengan nama lengkap bidang."
type: docs
weight: 290
url: /id/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

Mengimpor semua data bidang dari aliran JSON ke dalam bidang dokumen, mencocokkan bidang berdasarkan nama lengkapnya.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputJsonStream | Stream | Aliran JSON masukan yang berisi data bidang untuk diimpor ke bidang dokumen. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


