---
title: "Form.HasField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Memeriksa apakah formulir sudah memiliki bidang yang ditentukan"
type: docs
weight: 300
url: /id/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Periksa apakah formulir sudah memiliki bidang yang ditentukan.

```csharp
public bool HasField(Field field)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bidang | Bidang | Field untuk diperiksa. |

### Nilai Kembalian

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Form.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) atau [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field. |

### Nilai Kembalian

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Menentukan apakah bidang dengan nama yang ditentukan sudah ditambahkan ke Form, dengan kemampuan untuk melihat hierarki anak bidang.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) atau [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field. |
| searchChildren | Boolean | Ketika disetel ke `true` seluruh hierarki field formulir akan dicari untuk *fieldName* yang diminta (catatan bahwa dalam kasus ini [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) dari field yang diperlukan harus diberikan sebagai *fieldName*). |

### Nilai Kembalian

`true` jika nama field yang ditentukan ditambahkan ke Form; jika tidak, `false`.

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


