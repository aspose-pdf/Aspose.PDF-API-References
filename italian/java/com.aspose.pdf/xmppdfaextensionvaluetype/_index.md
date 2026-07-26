---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Lo schema PDF/A ValueType è richiesto per tutti i tipi di valore delle proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: -."
type: docs
weight: 5740
url: /it/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

Lo schema PDF/A ValueType è richiesto per tutti i tipi di valore di proprietà che non sono definiti nella specifica XMP 2004, cioè per i tipi di valore al di fuori della seguente lista: - Tipi di array (sono tipi contenitori che possono contenere uno o più campi): Alt, Bag, Seq - Tipi di valore di base: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipi di valore per la gestione dei media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo di valore base per Job/Workflow: Job - Tipi di valore dello schema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Namespace dello schema URI: http://www.aiim.org/pdfa/ns/type# Prefisso richiesto dello schema: pdfaType

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Inizializza un nuovo oggetto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Aggiungi nuovo campo. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Aggiunge l'intervallo di campi. |
| [clear](#clear--) | Cancella tutti i campi. |
| [getFields](#getFields--) | Ottiene l'elenco dei campi. |
| [getNamespaceUri](#getNamespaceUri--) | Ottiene l'URI dello spazio dei nomi. |
| [getPrefix](#getPrefix--) | Ottiene il prefisso. |
| [getType](#getType--) | Ottiene il tipo di valore. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Restituisce l'elenco degli elementi xml che rappresentano il campo nell'albero xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Restituisce l'elenco degli elementi xml che rappresentano il tipo di valore nell'albero xml. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Rimuove il campo dall'elenco dei campi. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Inizializza un nuovo oggetto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Aggiungi nuovo campo.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Aggiunge l'intervallo di campi.

### clear {#clear--}
```
public void clear()
```

Cancella tutti i campi.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Ottiene l'elenco dei campi.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Ottiene l'URI dello spazio dei nomi.

**Returns:**
Stringa

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Ottiene il prefisso.

**Returns:**
Stringa

### getType {#getType--}
```
public String getType()
```

Ottiene il tipo di valore.

**Returns:**
Stringa

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Restituisce l'elenco degli elementi xml che rappresentano il campo nell'albero xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Restituisce l'elenco degli elementi xml che rappresentano il tipo di valore nell'albero xml.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Rimuove il campo dall'elenco dei campi.
