---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF för Java API-referens"
description: "PDF/A ValueType-schemat krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004-specifikationen, dvs. för värdetyper utanför följande lista: -."
type: docs
weight: 5740
url: /sv/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

PDF/A ValueType-schema krävs för alla egenskapsvärdetyper som inte är definierade i XMP 2004-specifikationen, d.v.s. för värdetyper utanför följande lista: - Arraytyper (detta är behållartyper som kan innehålla ett eller flera fält): Alt, Bag, Seq - Grundläggande värdetyper: Boolean, (öppen och sluten) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management-värdetyper: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundläggande Jobb/Arbetsflöde-värdetyp: Job - EXIF-schema värdetyper: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schemanamnutrymme URI: http://www.aiim.org/pdfa/ns/type# Krävt schemanamns prefix: pdfaType

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initierar ett nytt objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Lägg till nytt fält. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Lägger till intervallet av fält. |
| [clear](#clear--) | Rensar alla fält. |
| [getFields](#getFields--) | Hämtar listan med fält. |
| [getNamespaceUri](#getNamespaceUri--) | Hämtar namnrymdens URI. |
| [getPrefix](#getPrefix--) | Hämtar prefixet. |
| [getType](#getType--) | Hämtar värdetypen. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Returnerar listan med xml-element som representerar fältet i xml-trädet. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Returnerar listan med xml-element som representerar värdetypen i xml-trädet. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Tar bort fältet från listan med fält. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initierar ett nytt objekt.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Lägg till nytt fält.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Lägger till intervallet av fält.

### clear {#clear--}
```
public void clear()
```

Rensar alla fält.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Hämtar listan med fält.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Hämtar namnrymdens URI.

**Returns:**
String

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Hämtar prefixet.

**Returns:**
String

### getType {#getType--}
```
public String getType()
```

Hämtar värdetypen.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Returnerar listan med xml-element som representerar fältet i xml-trädet.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Returnerar listan med xml-element som representerar värdetypen i xml-trädet.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Tar bort fältet från listan med fält.
