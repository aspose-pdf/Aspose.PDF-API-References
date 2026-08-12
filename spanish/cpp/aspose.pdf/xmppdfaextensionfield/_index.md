---
title: "Clase Aspose::Pdf::XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::XmpPdfAExtensionField class. Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema PDF/A Property Value Type, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema:  Prefijo requerido del espacio de nombres del esquema: pdfaField en C++."
type: docs
weight: 20300
url: /es/cpp/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class


Este esquema describe un campo en un tipo estructurado. Es muy similar al esquema PDF/A Property Value Type, pero define un campo en una estructura en lugar de una propiedad. URI del espacio de nombres del esquema: [http://www.aiim.org/pdfa/ns/field#](http://www.aiim.org/pdfa/ns/field#) Prefijo requerido del espacio de nombres del esquema: pdfaField.

```cpp
class XmpPdfAExtensionField : public Aspose::Pdf::XmpPdfAExtensionObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Name](./get_name/)() const | Nombre del campo. Los nombres de campo deben ser nombres de elemento XML válidos. |
| [get_ValueType](./get_valuetype/)() const | Tipo de valor del campo, tomado de la especificación XMP 2004, o de un esquema de extensión de tipo de valor PDF/A incrustado. Nombres de tipo XMP predefinidos o nombres de tipos personalizados. |
| [GetXml](./getxml/)(System::SharedPtr\<System::Xml::XmlDocument\>) override | Devuelve la lista de elementos xml que representan el campo en el árbol xml. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/)(const System::String\&, const System::String\&, const System::String\&, const System::String\&) | Inicializa el objeto. |
## Ver también

* Class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
