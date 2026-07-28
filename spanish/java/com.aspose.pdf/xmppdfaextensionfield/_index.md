---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema de Tipo de Valor de Propiedad PDF/A, pero define un campo en una estructura en lugar de una propiedad. Esquema."
type: docs
weight: 5690
url: /es/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema PDF/A Property Value Type, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/field# Prefijo de espacio de nombres requerido del esquema: pdfaField.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Inicializa el objeto. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getName](#getName--) | Nombre del campo. Los nombres de campo deben ser nombres de elemento XML válidos. |
| [getValueType](#getValueType--) | Tipo de valor del campo, tomado de la especificación XMP 2004, o de un esquema de extensión de tipo de valor PDF/A incrustado. Nombres de tipo XMP predefinidos o nombres de tipos personalizados. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Devuelve la lista de elementos xml que representan el campo en el árbol xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Devuelve la lista de elementos xml que representan el campo en el árbol xml. |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Inicializa el objeto.

### getName {#getName--}
```
public String getName()
```

Nombre del campo. Los nombres de campo deben ser nombres de elemento XML válidos.

**Returns:**
Cadena

### getValueType {#getValueType--}
```
public String getValueType()
```

Tipo de valor del campo, tomado de la especificación XMP 2004, o de un esquema de extensión de tipo de valor PDF/A incrustado. Nombres de tipo XMP predefinidos o nombres de tipos personalizados.

**Returns:**
Cadena

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Devuelve la lista de elementos xml que representan el campo en el árbol xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Devuelve la lista de elementos xml que representan el campo en el árbol xml.
