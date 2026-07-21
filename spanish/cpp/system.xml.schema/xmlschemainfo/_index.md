---
title: "Clase System::Xml::Schema::XmlSchemaInfo"
linktitle: "XmlSchemaInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaInfo. Representa el conjunto de información posterior a la validación del esquema de un nodo XML validado en C++."
type: docs
weight: 3800
url: /es/cpp/system.xml.schema/xmlschemainfo/
---
## XmlSchemaInfo class


Representa el conjunto de información post-validación de esquema de un nodo XML validado.

```cpp
class XmlSchemaInfo : public System::Xml::Schema::IXmlSchemaInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ContentType](./get_contenttype/)() | Devuelve el objeto [XmlSchemaContentType](../xmlschemacontenttype/) que corresponde al tipo de contenido de este nodo XML validado. |
| [get_IsDefault](./get_isdefault/)() override | Devuelve un valor que indica si este nodo XML validado se estableció como resultado de la aplicación de un valor predeterminado durante la validación del esquema XML [Schema](../) Lenguaje de Definición (XSD). |
| [get_IsNil](./get_isnil/)() override | Devuelve un valor que indica si el valor de este nodo XML validado es **nil**. |
| [get_MemberType](./get_membertype/)() override | Devuelve el tipo de esquema dinámico para este nodo XML validado. |
| [get_SchemaAttribute](./get_schemaattribute/)() override | Devuelve el objeto compilado [XmlSchemaAttribute](../xmlschemaattribute/) que corresponde a este nodo XML validado. |
| [get_SchemaElement](./get_schemaelement/)() override | Devuelve el objeto compilado [XmlSchemaElement](../xmlschemaelement/) que corresponde a este nodo XML validado. |
| [get_SchemaType](./get_schematype/)() override | Devuelve el tipo de esquema estático XML [Schema](../) Lenguaje de Definición (XSD) de este nodo XML validado. |
| [get_Validity](./get_validity/)() override | Devuelve el valor [XmlSchemaValidity](../xmlschemavalidity/) de este nodo XML validado. |
| [set_ContentType](./set_contenttype/)(XmlSchemaContentType) | Establece el objeto [XmlSchemaContentType](../xmlschemacontenttype/) que corresponde al tipo de contenido de este nodo XML validado. |
| [set_IsDefault](./set_isdefault/)(bool) | Establece un valor que indica si este nodo XML validado se estableció como resultado de la aplicación de un valor predeterminado durante la validación del esquema XML [Schema](../) Lenguaje de Definición (XSD). |
| [set_IsNil](./set_isnil/)(bool) | Establece un valor que indica si el valor de este nodo XML validado es **nil**. |
| [set_MemberType](./set_membertype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece el tipo de esquema dinámico para este nodo XML validado. |
| [set_SchemaAttribute](./set_schemaattribute/)(const SharedPtr\<XmlSchemaAttribute\>\&) | Establece el objeto compilado [XmlSchemaAttribute](../xmlschemaattribute/) que corresponde a este nodo XML validado. |
| [set_SchemaElement](./set_schemaelement/)(const SharedPtr\<XmlSchemaElement\>\&) | Establece el objeto compilado [XmlSchemaElement](../xmlschemaelement/) que corresponde a este nodo XML validado. |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaType\>\&) | Establece el tipo de esquema estático XML [Schema](../) Lenguaje de Definición (XSD) de este nodo XML validado. |
| [set_Validity](./set_validity/)(XmlSchemaValidity) | Establece el valor [XmlSchemaValidity](../xmlschemavalidity/) de este nodo XML validado. |
| [XmlSchemaInfo](./xmlschemainfo/)() | Inicializa una nueva instancia de la clase [XmlSchemaInfo](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [IXmlSchemaInfo](../ixmlschemainfo/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
