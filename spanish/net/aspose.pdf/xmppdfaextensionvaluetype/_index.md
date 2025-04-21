---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.XmpPdfAExtensionValueType. El esquema ValueType de PDF/A es requerido para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para tipos de valor fuera de la siguiente lista - Tipos de Array Alt, Bag, Seq - Tipos de valor básicos Boolean, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gestión de medios AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Job/Workflow Job - Tipos de valor del esquema EXIF Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI del espacio de nombres del esquema http//www.aiim.org/pdfa/ns/type Prefijo del espacio de nombres del esquema requerido pdfaType
type: docs
weight: 11490
url: /es/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## Clase XmpPdfAExtensionValueType

El esquema ValueType de PDF/A es requerido para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para tipos de valor fuera de la siguiente lista: - Tipos de Array (estos son tipos contenedores que pueden contener uno o más campos): Alt, Bag, Seq - Tipos de valor básicos: Boolean, (elección abierta y cerrada), Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipos de valor de gestión de medios: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipo de valor básico de Job/Workflow: Job - Tipos de valor del esquema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI del espacio de nombres del esquema: http://www.aiim.org/pdfa/ns/type# Prefijo del espacio de nombres del esquema requerido: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | Inicializa un nuevo objeto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Obtiene la descripción. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | Obtiene la lista de campos. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | Obtiene el URI del espacio de nombres. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | Obtiene el prefijo. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | Obtiene el tipo de valor. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Obtiene o establece el valor. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | Agrega un nuevo campo. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | Agrega el rango de campos. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | Limpia todos los campos. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | Devuelve la lista de elementos xml que representan el tipo de valor en el árbol xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | Elimina el campo de la lista de campos. |

### Véase también

* clase [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)