---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Tambahkan field dengan tipe yang ditentukan ke formulir
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Tambahkan field dengan tipe yang ditentukan ke formulir.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| fieldType | FieldType | Tipe field yang harus ditambahkan. |
| fieldName | String | Nama field yang harus ditambahkan. |
| pageNum | Int32 | Nomor halaman tempat field baru harus ditempatkan. |
| llx | Single | Abscissa dari sudut kiri bawah field. |
| lly | Single | Ordinate dari sudut kiri bawah field. |
| urx | Single | Abscissa dari sudut kanan atas field. |
| ury | Single | Ordinate dari sudut kanan atas field. |

### Return Value

true jika field berhasil ditambahkan.

## Contoh

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Lihat Juga

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Tambahkan field dengan tipe yang ditentukan ke formulir.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| fieldType | FieldType | Tipe field yang harus ditambahkan. |
| fieldName | String | Nama field yang harus ditambahkan. |
| initValue | String | Nilai awal dari field. |
| pageNum | Int32 | Nomor halaman tempat field baru harus ditempatkan. |
| llx | Single | Abscissa dari sudut kiri bawah field. |
| lly | Single | Ordinate dari sudut kiri bawah field. |
| urx | Single | Abscissa dari sudut kanan atas field. |
| ury | Single | Ordinate dari sudut kanan atas field. |

### Return Value

true jika field berhasil ditambahkan.

## Contoh

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Lihat Juga

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)