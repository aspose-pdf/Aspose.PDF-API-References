---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, kaynak PDF belgesi PDF spesifikasyonuna uymadığında PDF/A dönüşümünü kontrol etmek için bayrakları tutar. Bu sınıfın bayrakları kullanıldığında azalır."
type: docs
weight: 3740
url: /tr/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Bu sınıf, kaynak PDF belgesi PDF spesifikasyonuna uymadığında PDF/A dönüşümünü kontrol etmek için bayraklar tutar. Bu sınıfın bayrakları kullanıldığında performans düşer ancak kaynak PDF belgesi normal yolla PDF/A formatına dönüştürülemediğinde gereklidir. Varsayılan olarak tüm bayraklar false olarak ayarlanmıştır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Bazı PDF belgeleri, iç verilerde farklı adlara sahip yazı tipleri içerir. Bu bayrağın kullanımı, BaseFont ve FontDescriptor.FontName alanları farklı olduğunda özel işleme mantığını zorlar. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Bazı PDF belgeleri, iç verilerde farklı adlara sahip yazı tipleri içerir. Bu bayrağın kullanımı, BaseFont ve FontDescriptor.FontName alanları farklı olduğunda özel işleme mantığını zorlar. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Yapıcı

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Bazı PDF belgeleri, iç verilerde farklı adlara sahip yazı tipleri içerir. Bu bayrağın kullanımı, BaseFont ve FontDescriptor.FontName alanları farklı olduğunda özel işleme mantığını zorlar.

**Returns:**
boolean değer

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Bazı PDF belgeleri, iç verilerde farklı adlara sahip yazı tipleri içerir. Bu bayrağın kullanımı, BaseFont ve FontDescriptor.FontName alanları farklı olduğunda özel işleme mantığını zorlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
