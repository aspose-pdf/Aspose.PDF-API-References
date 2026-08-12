---
title: "System::Xml::Schema::XmlSchemaSimpleTypeUnion class"
linktitle: "XmlSchemaSimpleTypeUnion"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSimpleTypeUnion class. Representa el elemento union para tipos simples del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Un tipo de datos union puede usarse para especificar el contenido de un simpleType. El valor del elemento simpleType debe ser cualquiera de un conjunto de tipos de datos alternativos especificados en la union. Los tipos union son siempre tipos derivados y deben comprender al menos dos tipos de datos alternativos en C++."
type: docs
weight: 6600
url: /es/cpp/system.xml.schema/xmlschemasimpletypeunion/
---
## XmlSchemaSimpleTypeUnion class


Representa el elemento **union** para tipos simples del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Un tipo de datos **union** puede usarse para especificar el contenido de un **simpleType**. El valor del elemento **simpleType** debe ser cualquiera de un conjunto de tipos de datos alternativos especificados en la **union**. Los tipos **union** son siempre tipos derivados y deben comprender al menos dos tipos de datos alternativos.

```cpp
class XmlSchemaSimpleTypeUnion : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaseMemberTypes](./get_basemembertypes/)() | Devuelve una matriz de objetos [XmlSchemaSimpleType](../xmlschemasimpletype/) que representan el tipo del elemento **simpleType** basado en los valores de [XmlSchemaSimpleTypeUnion::get_BaseTypes](./get_basetypes/) y [XmlSchemaSimpleTypeUnion::get_MemberTypes](./get_membertypes/) del tipo simple. |
| [get_BaseTypes](./get_basetypes/)() | Devuelve la colección de tipos base. |
| [get_MemberTypes](./get_membertypes/)() | Devuelve la matriz de nombres de miembros calificados de tipos de datos incorporados o elementos **simpleType** definidos en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [set_MemberTypes](./set_membertypes/)(const ArrayPtr\<SharedPtr\<XmlQualifiedName\>\>\&) | Establece la matriz de nombres de miembros calificados de tipos de datos incorporados o elementos **simpleType** definidos en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [XmlSchemaSimpleTypeUnion](./xmlschemasimpletypeunion/)() | Inicializa una nueva instancia de la clase [XmlSchemaSimpleTypeUnion](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaSimpleTypeContent](../xmlschemasimpletypecontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
