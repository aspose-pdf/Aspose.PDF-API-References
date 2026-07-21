---
title: "clase Aspose::Pdf::XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "clase Aspose::Pdf::XmpPdfAExtensionValueType. El esquema PDF/A ValueType es necesario para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para tipos de valor fuera de la siguiente lista: en C++."
type: docs
weight: 20800
url: /es/cpp/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class


El esquema PDF/A ValueType es requerido para todos los tipos de valor de propiedad que no están definidos en la especificación XMP 2004, es decir, para tipos de valor fuera de la siguiente lista:

```cpp
class XmpPdfAExtensionValueType : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Agregar nuevo campo. |
| [AddRange](./addrange/)(const System::ArrayPtr\<System::SharedPtr\<XmpPdfAExtensionField\>\>\&) | Agrega el rango de campos. |
| [Clear](./clear/)() | Borra todos los campos. |
| [get_Fields](./get_fields/)() const | Obtiene la lista de campos. |
| [get_NamespaceUri](./get_namespaceuri/)() const | Obtiene el URI del espacio de nombres. |
| [get_Prefix](./get_prefix/)() const | Obtiene el prefijo. |
| [get_Type](./get_type/)() const | Obtiene el tipo de valor. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Devuelve la lista de elementos xml que representan el tipo de valor en el árbol xml. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionField\>\&) | Elimina el campo de la lista de campos. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Inicializa un nuevo objeto. |
## Observaciones


* Array types (these are container types which may contain one or more fields): Alt, Bag, Seq
* Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, [Text](../../aspose.pdf.text/), Thumbnail, URI, URL, XPath
* Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version
* Basic Job/Workflow value type: Job
* EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: [http://www.aiim.org/pdfa/ns/type#](http://www.aiim.org/pdfa/ns/type#) Required schema namespace prefix: pdfaType


## Ver también

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
