---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: CosPdfDictionary metodu. Belirtilen anahtara sahip öğeyi CosPdfDictionary'den kaldırır
type: docs
weight: 150
url: /tr/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Belirtilen anahtara sahip öğeyi [`CosPdfDictionary`](../)'den kaldırır.

```csharp
public bool Remove(string key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | String | Kaldırılacak öğenin anahtarı. |

### Dönüş Değeri

Öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca anahtar orijinal sözlükte bulunmadığında veya anahtar düzenlenebilir değilse false döner.

### Ayrıca Bakınız

* sınıf [CosPdfDictionary](../)
* ad alanı [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Belirli bir nesnenin ilk örneğini [`CosPdfDictionary`](../)'den kaldırır.

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | KeyValuePair`2 | [`CosPdfDictionary`](../)'den kaldırılacak nesne. |

### Dönüş Değeri

item [`CosPdfDictionary`](../)'den başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca item orijinal [`CosPdfDictionary`](../)'de bulunmadığında false döner.

### Ayrıca Bakınız

* arayüz [ICosPdfPrimitive](../../icospdfprimitive/)
* sınıf [CosPdfDictionary](../)
* ad alanı [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../../)