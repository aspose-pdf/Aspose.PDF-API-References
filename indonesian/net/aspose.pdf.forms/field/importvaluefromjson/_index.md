---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Metode Field. Mengimpor data ke dalam bidang yang ditentukan dari aliran JSON berdasarkan kecocokan tepat nama lengkap bidang
type: docs
weight: 210
url: /id/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Mengimpor data ke dalam bidang yang ditentukan dari aliran JSON, berdasarkan kecocokan tepat nama lengkap bidang.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputJsonStream | Stream | Aliran JSON input yang berisi data bidang yang akan diimpor ke dalam bidang. |

### Return Value

True jika bidang ditemukan dalam aliran JSON; jika tidak - false

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Lihat Juga

* kelas [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Mengimpor data ke dalam bidang yang ditentukan dari aliran JSON, menggunakan nama lengkap yang ditentukan dalam variabel 'fieldFullNameInJSON' untuk pencocokan.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputJsonStream | Stream | Aliran JSON input yang berisi data bidang yang akan diimpor ke dalam bidang. |
| fieldFullNameInJSON | String | Nama data dalam aliran JSON untuk pencocokan. Jika data dalam aliran JSON memiliki struktur bersarang, nama lengkap harus ditentukan dengan semua item induk dan anak dipisahkan oleh '.' |

### Return Value

True jika bidang ditemukan dalam file json; jika tidak - false

## Contoh

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Lihat Juga

* kelas [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)