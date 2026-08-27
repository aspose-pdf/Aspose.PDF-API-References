---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF/A ValueType şeması, XMP 2004 spesifikasyonunda tanımlanmamış tüm özellik değer tipleri için gereklidir, yani aşağıdaki listenin dışındaki değer tipleri için: -."
type: docs
weight: 5740
url: /tr/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

PDF/A ValueType şeması, XMP 2004 spesifikasyonunda tanımlanmamış tüm özellik değer türleri için gereklidir, yani aşağıdaki listedeki değer türlerinin dışındaki türler için:
- Dizi türleri (bir veya daha fazla alan içerebilen kapsayıcı türler): Alt, Bag, Seq
- Temel değer türleri: Boolean, (açık ve kapalı) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath
- Medya Yönetimi değer türleri: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
- Temel İş/İş Akışı değer türü: Job
- EXIF şema değer türleri: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational
Şema ad alanı URI: http://www.aiim.org/pdfa/ns/type# Gerekli şema ad alanı öneki: pdfaType

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Yeni nesneyi başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Yeni alan ekle. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Alan aralığını ekler. |
| [clear](#clear--) | Tüm alanları temizler. |
| [getFields](#getFields--) | Alanların listesini alır. |
| [getNamespaceUri](#getNamespaceUri--) | Ad alanı URI'sini alır. |
| [getPrefix](#getPrefix--) | Öneki alır. |
| [getType](#getType--) | Değer tipini alır. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | XML ağacında alanı temsil eden xml öğelerinin listesini döndürür. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | XML ağacında değer tipini temsil eden xml öğelerinin listesini döndürür. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Alanı alanların listesinden kaldırır. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Yeni nesneyi başlatır.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Yeni alan ekle.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Alan aralığını ekler.

### clear {#clear--}
```
public void clear()
```

Tüm alanları temizler.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Alanların listesini alır.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Ad alanı URI'sini alır.

**Returns:**
Dize

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Öneki alır.

**Returns:**
Dize

### getType {#getType--}
```
public String getType()
```

Değer tipini alır.

**Returns:**
Dize

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
XML ağacında alanı temsil eden xml öğelerinin listesini döndürür.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
XML ağacında değer tipini temsil eden xml öğelerinin listesini döndürür.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Alanı alanların listesinden kaldırır.
