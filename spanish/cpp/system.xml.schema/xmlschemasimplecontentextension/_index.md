---
title: "System::Xml::Schema::XmlSchemaSimpleContentExtension clase"
linktitle: "XmlSchemaSimpleContentExtension"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentExtension clase. Representa el elemento de extensión para contenido simple del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase puede usarse para derivar tipos simples mediante extensión. Tales derivaciones se utilizan para ampliar el contenido del tipo simple del elemento añadiendo atributos en C++."
type: docs
weight: 6000
url: /es/cpp/system.xml.schema/xmlschemasimplecontentextension/
---
## XmlSchemaSimpleContentExtension class


Representa el elemento **extension** para contenido simple del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase puede usarse para derivar tipos simples mediante extensión. Tales derivaciones se utilizan para ampliar el contenido del tipo simple del elemento añadiendo atributos.

```cpp
class XmlSchemaSimpleContentExtension : public System::Xml::Schema::XmlSchemaContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Devuelve el [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) que se usará para el valor del atributo. |
| [get_Attributes](./get_attributes/)() | Devuelve la colección de [XmlSchemaAttribute](../xmlschemaattribute/) y [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_BaseTypeName](./get_basetypename/)() | Devuelve el nombre de un tipo de datos incorporado o tipo simple del cual se extiende este tipo. |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Establece el [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) que se usará para el valor del atributo. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre de un tipo de datos incorporado o tipo simple del cual se extiende este tipo. |
| [XmlSchemaSimpleContentExtension](./xmlschemasimplecontentextension/)() | Inicializa una nueva instancia de la clase [XmlSchemaSimpleContentExtension](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaContent](../xmlschemacontent/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
