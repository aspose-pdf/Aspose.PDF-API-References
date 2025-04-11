---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke aliran yang disediakan
type: docs
weight: 240
url: /id/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke aliran yang disediakan.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran untuk menulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor bidang formulir ke JSON. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil dari operasi ekspor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Mengekspor bidang formulir PDF ke format JSON dan menulis hasilnya ke file yang ditentukan.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file untuk menulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor bidang formulir ke JSON. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil dari operasi ekspor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)