---
title: DictionaryEditor.TryGetValue
second_title: Aspose.PDF for .NET API Reference
description: DictionaryEditor metodu. string, name, bool, number gibi basit veri türlerine erişim için. Diğer türler için null döner.
type: docs
weight: 150
url: /tr/net/aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/
---
## DictionaryEditor.TryGetValue metodu

string, name, bool, number gibi basit veri türlerine erişim için. Diğer türler için null döner.

```csharp
public bool TryGetValue(string key, out ICosPdfPrimitive value)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | String | Anahtar değeri |
| value | ICosPdfPrimitive& | anahtar için [`ICosPdfPrimitive`](../../icospdfprimitive/) döner veya null. |

### Dönüş Değeri

Eğer [`ICosPdfPrimitive`](../../icospdfprimitive/) string, name, bool, number gibi ise true döner. Diğer tüm türler için false döner.

### Ayrıca Bakınız

* arayüz [ICosPdfPrimitive](../../icospdfprimitive/)
* sınıf [DictionaryEditor](../)
* ad alanı [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* derleme [Aspose.PDF](../../../)