---
title: "System::Xml::Schema::XmlSchemaSimpleContentRestriction clase"
linktitle: "XmlSchemaSimpleContentRestriction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaSimpleContentRestriction clase. Representa el elemento de restriction para contenido simple del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase puede usarse para derivar tipos simples mediante restricción. Tales derivaciones pueden usarse para limitar el rango de valores del elemento a un subconjunto de los valores especificados en el tipo simple heredado en C++."
type: docs
weight: 6100
url: /es/cpp/system.xml.schema/xmlschemasimplecontentrestriction/
---
## XmlSchemaSimpleContentRestriction class


Representa el elemento **restriction** para contenido simple del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase puede usarse para derivar tipos simples mediante restricción. Tales derivaciones pueden usarse para limitar el rango de valores del elemento a un subconjunto de los valores especificados en el tipo simple heredado.

```cpp
class XmlSchemaSimpleContentRestriction : public System::Xml::Schema::XmlSchemaContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Devuelve un [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) que se usará para el valor del atributo. |
| [get_Attributes](./get_attributes/)() | Devuelve la colección de [XmlSchemaAttribute](../xmlschemaattribute/) y [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/) de atributos para el tipo simple. |
| [get_BaseType](./get_basetype/)() | Devuelve el valor base del tipo simple. |
| [get_BaseTypeName](./get_basetypename/)() | Devuelve el nombre del tipo de datos incorporado o tipo simple del que se deriva este tipo. |
| [get_Facets](./get_facets/)() | Devuelve una faceta de [Xml](../../system.xml/)[Schema](../). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Establece un [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) que se usará para el valor del atributo. |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece el valor base del tipo simple. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre del tipo de datos incorporado o tipo simple del que se deriva este tipo. |
| [XmlSchemaSimpleContentRestriction](./xmlschemasimplecontentrestriction/)() | Inicializa una nueva instancia de la clase [XmlSchemaSimpleContentRestriction](./). |
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
