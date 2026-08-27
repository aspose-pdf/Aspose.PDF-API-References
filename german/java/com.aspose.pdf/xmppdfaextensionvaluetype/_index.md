---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das PDF/A ValueType‑Schema ist für alle Eigenschafts‑Wertetypen erforderlich, die nicht in der XMP‑2004‑Spezifikation definiert sind, d. h. für Wertetypen außerhalb der folgenden Liste: -."
type: docs
weight: 5740
url: /de/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

Das PDF/A ValueType Schema ist für alle Eigenschaftswerttypen erforderlich, die nicht in der XMP‑2004‑Spezifikation definiert sind, d. h. für Werttypen außerhalb der folgenden Liste: - Array‑Typen (dies sind Containertypen, die ein oder mehrere Felder enthalten können): Alt, Bag, Seq - Grundwerttypen: Boolean, (offene und geschlossene) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media‑Management‑Werttypen: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Grundlegender Job/Workflow‑Werttyp: Job - EXIF‑Schema‑Werttypen: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema-Namespace-URI: http://www.aiim.org/pdfa/ns/type# Erforderliches Schema-Namespace-Präfix: pdfaType

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initialisiert ein neues Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Neues Feld hinzufügen. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Fügt den Bereich der Felder hinzu. |
| [clear](#clear--) | Löscht alle Felder. |
| [getFields](#getFields--) | Gibt die Liste der Felder zurück. |
| [getNamespaceUri](#getNamespaceUri--) | Liefert die Namespace-URI. |
| [getPrefix](#getPrefix--) | Liefert das Präfix. |
| [getType](#getType--) | Gibt den Wertetyp zurück. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Gibt die Liste der XML-Elemente zurück, die das Feld im XML-Baum darstellen. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Gibt die Liste der XML-Elemente zurück, die den Wertetyp im XML-Baum darstellen. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Entfernt das Feld aus der Liste der Felder. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Initialisiert ein neues Objekt.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Neues Feld hinzufügen.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Fügt den Bereich der Felder hinzu.

### clear {#clear--}
```
public void clear()
```

Löscht alle Felder.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Gibt die Liste der Felder zurück.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Liefert die Namespace-URI.

**Returns:**
String

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Liefert das Präfix.

**Returns:**
String

### getType {#getType--}
```
public String getType()
```

Gibt den Wertetyp zurück.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Gibt die Liste der XML-Elemente zurück, die das Feld im XML-Baum darstellen.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Gibt die Liste der XML-Elemente zurück, die den Wertetyp im XML-Baum darstellen.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Entfernt das Feld aus der Liste der Felder.
