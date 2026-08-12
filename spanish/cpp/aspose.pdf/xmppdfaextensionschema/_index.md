---
title: "Aspose::Pdf::XmpPdfAExtensionSchema clase"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::XmpPdfAExtensionSchema clase. Describe el esquema de extensión XMP que es proporcionado por PDF/A-1 en C++."
type: docs
weight: 20600
url: /es/cpp/aspose.pdf/xmppdfaextensionschema/
---
## XmpPdfAExtensionSchema class


Describe el esquema de extensión XMP que es proporcionado por PDF/A-1.

```cpp
class XmpPdfAExtensionSchema : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Agrega un nuevo objeto al esquema. |
| [Contains](./contains/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Determina si el obj existe en el esquema. |
| [get_Description](./get_description/)() const | Obtiene la descripción del esquema. |
| [get_Objects](./get_objects/)() const | Obtiene la lista de objetos (propiedades, tipos de valor). |
| [GetProperty](./getproperty/)(const System::String\&) | Devuelve la propiedad PDF/A por su nombre. |
| [GetSchemaXml](./getschemaxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Devuelve el elemento xml (etiqueta - li) que representa el esquema en el árbol xml. |
| [GetValuesXml](./getvaluesxml/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&, const System::SharedPtr\<System::Xml::XmlElement\>\&) | Obtiene los valores de las propiedades como representación de árbol xml. |
| [Remove](./remove/)(const System::SharedPtr\<XmpPdfAExtensionObject\>\&) | Elimina el objeto del esquema. |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/)(const System::SharedPtr\<XmpPdfAExtensionSchemaDescription\>\&) | Inicializa un nuevo objeto. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultExtensionNamespacePrefix](./defaultextensionnamespaceprefix/) | Prefijo de espacio de nombres de extensión predeterminado. |
| static [DefaultExtensionNamespaceUri](./defaultextensionnamespaceuri/) | URI de espacio de nombres de extensión predeterminado. |
| static [DefaultFieldNamespacePrefix](./defaultfieldnamespaceprefix/) | Prefijo de espacio de nombres de campo predeterminado. |
| static [DefaultFieldNamespaceUri](./defaultfieldnamespaceuri/) | URI de espacio de nombres de extensión predeterminado. |
| static [DefaultPropertyNamespacePrefix](./defaultpropertynamespaceprefix/) | Prefijo de espacio de nombres de propiedad predeterminado. |
| static [DefaultPropertyNamespaceUri](./defaultpropertynamespaceuri/) | URI de espacio de nombres de propiedad predeterminado. |
| static [DefaultSchemaNamespacePrefix](./defaultschemanamespaceprefix/) | Prefijo de espacio de nombres de esquema predeterminado. |
| static [DefaultSchemaNamespaceUri](./defaultschemanamespaceuri/) | URI de espacio de nombres de esquema predeterminado. |
| static [DefaultValueNamespaceUri](./defaultvaluenamespaceuri/) | URI de espacio de nombres de valor predeterminado. |
| static [DefaultValueTypeNamespacePrefix](./defaultvaluetypenamespaceprefix/) | Prefijo de espacio de nombres de tipo de valor predeterminado. |
| static [RdfNamespaceURI](./rdfnamespaceuri/) | URI de espacio de nombres rdf predeterminado. |
| static [RdfPrefix](./rdfprefix/) | Prefijo de espacio de nombres rdf predeterminado. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
