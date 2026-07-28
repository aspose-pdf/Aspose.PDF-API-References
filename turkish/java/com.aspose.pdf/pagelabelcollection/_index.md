---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfa etiketi koleksiyonunu temsil eden sınıf."
type: docs
weight: 3400
url: /tr/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Sayfa etiketi koleksiyonunu temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLabel](#getLabel-int-) | Sayfa indeksine göre sayfa etiketini alır (sayfa indeksi 0'dan başlar). |
| [getPages](#getPages--) | Koleksiyondaki sayfa indekslerini alır. |
| [removeLabel](#removeLabel-int-) | Sayfa indeksine göre etiketi kaldırır (sayfa indeksi 0'dan başlar). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Verilen sayfa indeksi için etiketi günceller (sayfa indeksi 0'dan başlar). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Sayfa indeksine göre sayfa etiketini alır (sayfa indeksi 0'dan başlar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageIndex |  | Sayfanın indeksi. |

**Returns:**
Belirtilen sayfa indeksi için sayfa etiketi veya etiket yoksa null.

### getPages {#getPages--}
```
public int[] getPages()
```

Koleksiyondaki sayfa indekslerini alır.

**Returns:**
Sayfaların indekslerini içeren tamsayı dizisi.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Sayfa indeksine göre etiketi kaldırır (sayfa indeksi 0'dan başlar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageIndex |  | Etiketin silinmesi gereken sayfanın indeksi. |

**Returns:**
İşlem başarılı bir şekilde yürütüldüyse true.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Verilen sayfa indeksi için etiketi günceller (sayfa indeksi 0'dan başlar).
