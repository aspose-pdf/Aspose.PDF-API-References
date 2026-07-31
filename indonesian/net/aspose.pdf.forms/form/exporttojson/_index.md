---
title: "Form.ExportToJson"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengekspor field formulir PDF ke format JSON dan menulis hasilnya ke stream yang disediakan"
type: docs
weight: 260
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
| stream | Stream | Stream untuk menulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor field formulir ke JSON. |

### Nilai Kembalian

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil operasi ekspor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Lihat Juga

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
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
| fileName | String | Nama file yang akan ditulis output JSON. |
| options | ExportFieldsToJsonOptions | Pengaturan opsional untuk mengekspor field formulir ke JSON. |

### Nilai Kembalian

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil operasi ekspor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Lihat Juga

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


