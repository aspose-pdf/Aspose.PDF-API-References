---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengekspor konten dari field pdf ke dalam aliran xml. Nilai field tombol tidak akan diekspor
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/form/exportxml/
---
## Metode Form.ExportXml

Mengekspor konten dari field pdf ke dalam aliran xml. Nilai field tombol tidak akan diekspor.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputXmlStream | Stream | Aliran Xml keluaran. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)