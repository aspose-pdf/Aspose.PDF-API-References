---
title: "Clase System::Xml::Schema::XmlSchemaSimpleTypeList"
linktitle: "XmlSchemaSimpleTypeList"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaSimpleTypeList. Representa el elemento list del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase puede usarse para definir un elemento simpleType como una lista de valores de un tipo de datos especificado en C++."
type: docs
weight: 6400
url: /es/cpp/system.xml.schema/xmlschemasimpletypelist/
---
## XmlSchemaSimpleTypeList class


Representa el elemento **list** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase puede usarse para definir un elemento **simpleType** como una lista de valores de un tipo de datos especificado.

```cpp
class XmlSchemaSimpleTypeList : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaseItemType](./get_baseitemtype/)() | Devuelve el [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo del elemento **simpleType** basado en los valores de [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) y [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) del tipo simple. |
| [get_ItemType](./get_itemtype/)() | Devuelve el elemento **simpleType** que se deriva del tipo especificado por el valor base. |
| [get_ItemTypeName](./get_itemtypename/)() | Devuelve el nombre de un tipo de datos incorporado o del elemento **simpleType** definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [set_BaseItemType](./set_baseitemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece el [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo del elemento **simpleType** basado en los valores de [XmlSchemaSimpleTypeList::get_ItemType](./get_itemtype/) y [XmlSchemaSimpleTypeList::get_ItemTypeName](./get_itemtypename/) del tipo simple. |
| [set_ItemType](./set_itemtype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece el elemento **simpleType** que se deriva del tipo especificado por el valor base. |
| [set_ItemTypeName](./set_itemtypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre de un tipo de datos incorporado o del elemento **simpleType** definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [XmlSchemaSimpleTypeList](./xmlschemasimpletypelist/)() | Inicializa una nueva instancia de la clase [XmlSchemaSimpleTypeList](./). |
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
