---
title: "Clase System::Xml::Schema::XmlSchemaAttributeGroup"
linktitle: "XmlSchemaAttributeGroup"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaAttributeGroup. Representa el elemento **attributeGroup** del XML Schema según lo especificado por el World Wide Web Consortium (W3C). AttributesGroups proporciona un mecanismo para agrupar un conjunto de declaraciones de atributos de modo que puedan incorporarse como un grupo en definiciones de tipos complejos en C++."
type: docs
weight: 1200
url: /es/cpp/system.xml.schema/xmlschemaattributegroup/
---
## XmlSchemaAttributeGroup class


Representa el elemento **attributeGroup** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). AttributesGroups proporciona un mecanismo para agrupar un conjunto de declaraciones de atributos de modo que puedan incorporarse como un grupo en definiciones de tipos complejos.

```cpp
class XmlSchemaAttributeGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AnyAttribute](./get_anyattribute/)() | Devuelve el componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del grupo de atributos. |
| [get_Attributes](./get_attributes/)() | Devuelve la colección de atributos del grupo de atributos. Contiene los elementos [XmlSchemaAttribute](../xmlschemaattribute/) y [XmlSchemaAttributeGroupRef](../xmlschemaattributegroupref/). |
| [get_Name](./get_name/)() | Devuelve el nombre del grupo de atributos. |
| [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado del grupo de atributos. |
| [get_RedefinedAttributeGroup](./get_redefinedattributegroup/)() | Devuelve la propiedad de grupo de atributos redefinida del XML [Schema](../). |
| [set_AnyAttribute](./set_anyattribute/)(const SharedPtr\<XmlSchemaAnyAttribute\>\&) | Establece el componente [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) del grupo de atributos. |
| [set_Name](./set_name/)(const String\&) | Establece el nombre del grupo de atributos. |
| [XmlSchemaAttributeGroup](./xmlschemaattributegroup/)() | Inicializa una nueva instancia de la clase [XmlSchemaAttributeGroup](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaAnnotated](../xmlschemaannotated/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
