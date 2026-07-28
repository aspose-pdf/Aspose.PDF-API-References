---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "XSL-FO dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder."
type: docs
weight: 5780
url: /tr/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

XSL-FO dosyasını pdf belgesine yükleme/içe aktarma seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBasePath](#getBasePath--) | Temel yol/url, yüklü SVG dosyasında başvurulan dış kaynaklara (varsa) göreceli yolların aranacağı yerdir. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu hataların işlenmesi için olası stratejileri listeler. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu hataların işlenmesi için olası stratejileri listeler. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Oluşturur {@code XslFoLoadOptions} nesnesini xsl verisi olmadan.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Temel yol/url, yüklü SVG dosyasında başvurulan dış kaynaklara (varsa) göreceli yolların aranacağı yerdir.

**Returns:**
Dize

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu hataların işlenmesi için olası stratejileri listeler.

**Returns:**
ParsingErrorsHandlingTypes ögesi @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Kaynak XSLFO belgesi biçimlendirme hataları içerebilir. Bu enum, bu hataların işlenmesi için olası stratejileri listeler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingErrorsHandlingType |  | ParsingErrorsHandlingTypes ögesi @see ParsingErrorsHandlingTypes |
