---
title: "Form.ExportXml"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengekspor konten bidang-bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

Mengekspor konten bidang pdf ke dalam aliran xml. Nilai bidang tombol tidak akan diekspor.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputXmlStream | Stream | Aliran Xml output. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


