---
title: "Field.ExportValueToJson"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Field. Mengekspor konten bidang yang ditentukan ke aliran JSON. Nilai bidang tombol tidak diekspor."
type: docs
weight: 180
url: /id/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

Mengekspor konten bidang yang ditentukan ke aliran JSON. Nilai bidang tombol tidak diekspor.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputJsonStream | Stream | Aliran JSON output tempat data bidang akan ditulis. |
| diindent | Boolean | Opsional. Menentukan apakah output JSON harus diindent untuk meningkatkan keterbacaan. Nilai default adalah true. |

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Lihat Juga

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


