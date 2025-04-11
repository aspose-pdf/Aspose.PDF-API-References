---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Field. Mengekspor konten dari field yang ditentukan ke dalam aliran JSON. Nilai field tombol tidak diekspor
type: docs
weight: 180
url: /id/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Metode Field.ExportValueToJson

Mengekspor konten dari field yang ditentukan ke dalam aliran JSON. Nilai field tombol tidak diekspor.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputJsonStream | Stream | Aliran JSON keluaran di mana data field akan ditulis. |
| indented | Boolean | Opsional. Menentukan apakah keluaran JSON harus diindentas untuk keterbacaan yang lebih baik. Nilai default adalah true. |

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Lihat Juga

* kelas [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)