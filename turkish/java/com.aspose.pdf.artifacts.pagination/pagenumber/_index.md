---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir indeks, toplam sayfa sayısı ve bir ayraç içeren sayfa numarası formatını temsil eder."
type: docs
weight: 150
url: /tr/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Bir indeks, toplam sayfa sayısı ve bir ayraç içeren sayfa numarası formatını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Sayfa numarası biçiminde kullanılan ayırıcıyı alır veya ayarlar. Biçimlendirilmiş dize, belirtilen ayırıcıya göre güncellenecektir. |
| [getIndex](#getIndex--) | Sayfa numarası biçiminin sayfa indeksi bileşenini alır veya ayarlar. Biçimlendirilmiş dize, sayfa indeksi için bir yer tutucu içerecektir. |
| [getOffset](#getOffset--) | Sayfa indeksine eklenecek ofseti alır veya ayarlar. |
| [getPageNumberString](#getPageNumberString-int-int-) | Geçerli ayarlara göre sayfa numarasını temsil eden biçimlendirilmiş bir dize döndürür. |
| [getTotalNum](#getTotalNum--) | Sayfa numarası biçiminin toplam sayfa sayısı bileşenini alır veya ayarlar. Biçimlendirilmiş dize, toplam sayfa sayısı için bir yer tutucu içerecektir. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Sayfa numarası biçiminde kullanılan ayırıcıyı alır veya ayarlar. Biçimlendirilmiş dize, belirtilen ayırıcıya göre güncellenecektir. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Sayfa numarası biçiminin sayfa indeksi bileşenini alır veya ayarlar. |
| [setOffset](#setOffset-int-) | Sayfa indeksine eklenecek ofseti alır veya ayarlar. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Sayfa numarası biçiminin toplam sayfa sayısı bileşenini alır veya ayarlar. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Sayfa numarası biçiminde kullanılan ayırıcıyı alır veya ayarlar. Biçimlendirilmiş dize, belirtilen ayırıcıya göre güncellenecektir.

**Returns:**
String değeri

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Sayfa numarası biçiminin sayfa indeksi bileşenini alır veya ayarlar. Biçimlendirilmiş dize, sayfa indeksi için bir yer tutucu içerecektir.

**Returns:**
PageIndex örneği

### getOffset {#getOffset--}
```
public final int getOffset()
```

Sayfa indeksine eklenecek ofseti alır veya ayarlar.

**Returns:**
int değer

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Geçerli ayarlara göre sayfa numarasını temsil eden biçimlendirilmiş bir dize döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Mevcut sayfa numarası. |
| sayım |  | Toplam sayfa sayısı. |

**Returns:**
Biçimlendirilmiş bir sayfa numarası dizesi.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Sayfa numarası biçiminin toplam sayfa sayısı bileşenini alır veya ayarlar. Biçimlendirilmiş dize, toplam sayfa sayısı için bir yer tutucu içerecektir.

**Returns:**
PageTotalNum örneği

### setDelimiter {#setDelimiter-java.lang.String-}
Sayfa numarası biçiminde kullanılan ayırıcıyı alır veya ayarlar. Biçimlendirilmiş dize, belirtilen ayırıcıya göre güncellenecektir.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Sayfa numarası biçiminin sayfa indeksi bileşenini alır veya ayarlar.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Sayfa indeksine eklenecek ofseti alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Sayfa numarası biçiminin toplam sayfa sayısı bileşenini alır veya ayarlar.
