---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengimpor bidang formulir PDF dari format JSON yang disediakan dalam aliran
type: docs
weight: 290
url: /id/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Mengimpor bidang formulir PDF dari format JSON yang disediakan dalam aliran.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran untuk membaca input JSON dari. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil operasi impor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Mengimpor bidang formulir PDF dari format JSON yang disediakan dalam file yang ditentukan.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileName | String | Nama file untuk membaca input JSON dari. |

### Nilai Kembali

Koleksi dari [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) yang menunjukkan hasil operasi impor untuk setiap bidang formulir.

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Lihat Juga

* kelas [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)