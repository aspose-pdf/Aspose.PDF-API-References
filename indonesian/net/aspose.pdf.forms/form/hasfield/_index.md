---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Periksa apakah formulir sudah memiliki field yang ditentukan
type: docs
weight: 280
url: /id/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Periksa apakah formulir sudah memiliki field yang ditentukan.

```csharp
public bool HasField(Field field)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| field | Field | Field yang akan diperiksa. |

### Nilai Kembali

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* kelas [Field](../../field/)
* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Menentukan apakah field dengan nama yang ditentukan sudah ditambahkan ke Form.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) atau [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field. |

### Nilai Kembali

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Menentukan apakah field dengan nama yang ditentukan sudah ditambahkan ke Form, dengan kemampuan untuk melihat ke dalam hierarki anak field.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) atau [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field. |
| searchChildren | Boolean | Ketika diatur ke `true`, seluruh hierarki field formulir akan dicari untuk *fieldName* yang diminta (perhatikan bahwa dalam kasus ini [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field yang diperlukan harus diberikan sebagai *fieldName*). |

### Nilai Kembali

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)