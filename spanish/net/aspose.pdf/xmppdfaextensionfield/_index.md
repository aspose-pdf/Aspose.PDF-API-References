---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.XmpPdfAExtensionField. Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema de Tipo de Valor de Propiedad PDF/A, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema http//www.aiim.org/pdfa/ns/field Prefijo del espacio de nombres del esquema requerido pdfaField
type: docs
weight: 11440
url: /es/net/aspose.pdf/xmppdfaextensionfield/
---
## Clase XmpPdfAExtensionField

Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema de Tipo de Valor de Propiedad PDF/A, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/field# Prefijo del espacio de nombres del esquema requerido: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Inicializa el objeto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Obtiene la descripción. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Nombre del campo. Los nombres de los campos deben ser nombres de elementos XML válidos. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Obtiene o establece el valor. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Tipo de valor del campo, extraído de la Especificación XMP 2004, o un esquema de extensión de tipo de valor PDF/A incrustado. Nombres de tipos XMP predefinidos o nombres de tipos personalizados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Devuelve la lista de elementos xml que representan el campo en el árbol xml. |

### Véase también

* clase [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)