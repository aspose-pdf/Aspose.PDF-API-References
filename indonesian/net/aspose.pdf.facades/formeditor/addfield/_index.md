---
title: "FormEditor.AddField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menambahkan bidang dengan tipe yang ditentukan ke formulir"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Tambahkan bidang dengan tipe yang ditentukan ke formulir.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldType | FieldType | Tipe bidang yang harus ditambahkan. |
| fieldName | String | Nama bidang yang harus ditambahkan. |
| pageNum | Int32 | Nomor halaman tempat bidang baru harus ditempatkan. |
| llx | Single | Absis sudut kiri bawah bidang. |
| lly | Single | Ordinat sudut kiri bawah bidang. |
| urx | Single | Absis sudut kanan atas bidang. |
| ury | Single | Ordinat sudut kanan atas bidang. |

### Nilai Kembalian

true jika bidang berhasil ditambahkan.

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

Tambahkan bidang dengan tipe yang ditentukan ke formulir.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldType | FieldType | Tipe bidang yang harus ditambahkan. |
| fieldName | String | Nama bidang yang harus ditambahkan. |
| initValue | String | Nilai awal bidang. |
| pageNum | Int32 | Nomor halaman tempat bidang baru harus ditempatkan. |
| llx | Single | Absis sudut kiri bawah bidang. |
| lly | Single | Ordinat sudut kiri bawah bidang. |
| urx | Single | Absis sudut kanan atas bidang. |
| ury | Single | Ordinat sudut kanan atas bidang. |

### Nilai Kembalian

true jika bidang berhasil ditambahkan.

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


