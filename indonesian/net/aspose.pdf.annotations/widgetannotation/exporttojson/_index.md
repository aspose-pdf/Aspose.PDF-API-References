---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Metode WidgetAnnotation. Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke aliran yang disediakan
type: docs
weight: 120
url: /id/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke aliran yang disediakan.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran untuk menulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor bidang formulir ke JSON. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil dari operasi ekspor untuk bidang formulir yang ditentukan dan elemen anaknya, jika ada.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* kelas [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Mengekspor bidang formulir PDF yang ditentukan ke format JSON dan menulis hasilnya ke file yang ditentukan.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file untuk menulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor bidang formulir ke JSON. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil dari operasi ekspor untuk bidang formulir yang ditentukan dan elemen anaknya, jika ada.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* kelas [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)