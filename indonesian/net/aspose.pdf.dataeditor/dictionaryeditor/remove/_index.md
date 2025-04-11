---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: Metode DictionaryEditor. Menghapus elemen dengan kunci yang ditentukan dari DictionaryEditor
type: docs
weight: 140
url: /id/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Menghapus elemen dengan kunci yang ditentukan dari [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci elemen yang akan dihapus. |

### Return Value

True jika elemen berhasil dihapus; jika tidak, false. Metode ini juga mengembalikan false jika kunci tidak ditemukan dalam kamus asli atau kunci tidak dapat diedit.

### See Also

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Menghapus kemunculan pertama dari objek tertentu dari [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | KeyValuePair`2 | Objek yang akan dihapus dari [`DictionaryEditor`](../). |

### Return Value

true jika item berhasil dihapus dari [`DictionaryEditor`](../); jika tidak, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam [`DictionaryEditor`](../).

### See Also

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)