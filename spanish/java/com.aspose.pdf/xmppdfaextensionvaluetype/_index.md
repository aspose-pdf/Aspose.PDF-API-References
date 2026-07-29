---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El esquema ValueType de PDF/A es necesario para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para tipos de valor fuera de la siguiente lista: -."
type: docs
weight: 5740
url: /es/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

El esquema PDF/A ValueType es necesario para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para los tipos de valor fuera de la siguiente lista: - Tipos de matriz (son tipos contenedores que pueden contener uno o más campos): Alt, Bag, Seq - Tipos de valor básicos: Boolean, (abierta y cerrada) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gestión de medios: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de trabajo/flujo: Job - Tipos de valor del esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/type# Prefijo de espacio de nombres requerido del esquema: pdfaType

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Inicializa un nuevo objeto. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Agregar nuevo campo. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Agrega el rango de campos. |
| [clear](#clear--) | Borra todos los campos. |
| [getFields](#getFields--) | Obtiene la lista de campos. |
| [getNamespaceUri](#getNamespaceUri--) | Obtiene el URI del espacio de nombres. |
| [getPrefix](#getPrefix--) | Obtiene el prefijo. |
| [getType](#getType--) | Obtiene el tipo de valor. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Devuelve la lista de elementos xml que representan el campo en el árbol xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Devuelve la lista de elementos xml que representan el tipo de valor en el árbol xml. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Elimina el campo de la lista de campos. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Inicializa un nuevo objeto.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Agregar nuevo campo.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Agrega el rango de campos.

### clear {#clear--}
```
public void clear()
```

Borra todos los campos.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Obtiene la lista de campos.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Obtiene el URI del espacio de nombres.

**Returns:**
Cadena

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Obtiene el prefijo.

**Returns:**
Cadena

### getType {#getType--}
```
public String getType()
```

Obtiene el tipo de valor.

**Returns:**
Cadena

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Devuelve la lista de elementos xml que representan el campo en el árbol xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Devuelve la lista de elementos xml que representan el tipo de valor en el árbol xml.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Elimina el campo de la lista de campos.
