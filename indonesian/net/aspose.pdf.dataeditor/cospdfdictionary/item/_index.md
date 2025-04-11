---
title: CosPdfDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: Properti CosPdfDictionary. Mengambil atau mengatur elemen dengan kunci yang ditentukan
type: docs
weight: 60
url: /id/net/aspose.pdf.dataeditor/cospdfdictionary/item/
---
## CosPdfDictionary indexer

Mengambil atau mengatur elemen dengan kunci yang ditentukan.

```csharp
public ICosPdfPrimitive this[string key] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| key | Kunci elemen yang akan diambil atau diatur. |

### Return Value

Elemen dengan kunci yang ditentukan.

### Exceptions

| exception | kondisi |
| --- | --- |
| ArgumentNullException | Kunci adalah null. |
| KeyNotFoundException | Properti diambil dan kunci tidak ditemukan. |
| ArgumentException | Lempar pengecualian jika kunci tidak dapat diedit/diatur. |

### See Also

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [CosPdfDictionary](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)