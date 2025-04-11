---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor metodu. Belirtilen anahtara sahip öğeyi DictionaryEditor'dan kaldırır
type: docs
weight: 140
url: /tr/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Belirtilen anahtara sahip öğeyi [`DictionaryEditor`](../)'dan kaldırır.

```csharp
public bool Remove(string key)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | String | Kaldırılacak öğenin anahtarı. |

### Dönüş Değeri

Öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca anahtar orijinal sözlükte bulunmadığında veya anahtar düzenlenebilir değilse false döner.

### Ayrıca Bakınız

* sınıf [DictionaryEditor](../)
* ad alanı [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Belirli bir nesnenin ilk örneğini [`DictionaryEditor`](../)'dan kaldırır.

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | KeyValuePair`2 | [`DictionaryEditor`](../)'dan kaldırılacak nesne. |

### Dönüş Değeri

item başarıyla [`DictionaryEditor`](../)'dan kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca item orijinal [`DictionaryEditor`](../)'da bulunmadığında false döner.

### Ayrıca Bakınız

* arayüz [ICosPdfPrimitive](../../icospdfprimitive/)
* sınıf [DictionaryEditor](../)
* ad alanı [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../../)