---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır."
type: docs
weight: 3440
url: /tr/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Sayfa numarası damgasını temsil eder ve sayfaları numaralandırmak için kullanılır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | {@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır. |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | {@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır. |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | {@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat](#getFormat--) | Sayfa numaralarını damgalamak için String değerini alır. Değer, damgalama işlemi sırasında sayfa numarasıyla değiştirilen '#' karakterini içermelidir. |
| [getNumberingStyle](#getNumberingStyle--) | Bu damga tarafından kullanılan numaralandırma stili. |
| [getStartingNumber](#getStartingNumber--) | Başlangıç sayfasının numarasının değerini alır. Diğer sayfalar bu değerden başlayarak numaralandırılır. |
| [put](#put-com.aspose.pdf.Page-) | Sayfa numarası ekler. |
| [setFormat](#setFormat-java.lang.String-) | Sayfa numaralarını damgalamak için dize değerini ayarlar. Değer, damgalama sürecinde sayfa numarasıyla değiştirilen '#' karakterini içermelidir. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Bu damga tarafından kullanılan numaralandırma stili. |
| [setStartingNumber](#setStartingNumber-int-) | Başlangıç sayfasının numarasının değerini ayarlar. Diğer sayfalar bu değerden başlayarak numaralandırılır. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

{@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır.

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
{@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır.

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
{@code PageNumberStamp} sınıfının yeni bir örneğini başlatır. Biçim "#" olarak ayarlanır.

### getFormat {#getFormat--}
```
public String getFormat()
```

Sayfa numaralarını damgalamak için String değerini alır. Değer, damgalama işlemi sırasında sayfa numarasıyla değiştirilen '#' karakterini içermelidir.

**Returns:**
String değeri

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Bu damga tarafından kullanılan numaralandırma stili.

**Returns:**
NumberingStyle değeri @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Başlangıç sayfasının numarasının değerini alır. Diğer sayfalar bu değerden başlayarak numaralandırılır.

**Returns:**
int değer

### put {#put-com.aspose.pdf.Page-}
Sayfa numarası ekler.

### setFormat {#setFormat-java.lang.String-}
Sayfa numaralarını damgalamak için dize değerini ayarlar. Değer, damgalama sürecinde sayfa numarasıyla değiştirilen '#' karakterini içermelidir.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Bu damga tarafından kullanılan numaralandırma stili.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Başlangıç sayfasının numarasının değerini ayarlar. Diğer sayfalar bu değerden başlayarak numaralandırılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
