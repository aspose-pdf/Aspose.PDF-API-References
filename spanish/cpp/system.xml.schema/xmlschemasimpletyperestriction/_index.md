---
title: "Clase System::Xml::Schema::XmlSchemaSimpleTypeRestriction"
linktitle: "XmlSchemaSimpleTypeRestriction"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaSimpleTypeRestriction. Representa el elemento restriction para tipos simples del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Esta clase puede usarse restringiendo el elemento simpleType en C++."
type: docs
weight: 6500
url: /es/cpp/system.xml.schema/xmlschemasimpletyperestriction/
---
## XmlSchemaSimpleTypeRestriction class


Representa el elemento **restriction** para tipos simples del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Esta clase puede usarse restringiendo el elemento **simpleType**.

```cpp
class XmlSchemaSimpleTypeRestriction : public System::Xml::Schema::XmlSchemaSimpleTypeContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaseType](./get_basetype/)() | Devuelve información sobre el tipo base. |
| [get_BaseTypeName](./get_basetypename/)() | Devuelve el nombre del tipo base calificado. |
| [get_Facets](./get_facets/)() | Devuelve una faceta de [Xml](../../system.xml/)[Schema](../). |
| [set_BaseType](./set_basetype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece información sobre el tipo base. |
| [set_BaseTypeName](./set_basetypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre del tipo base calificado. |
| [XmlSchemaSimpleTypeRestriction](./xmlschemasimpletyperestriction/)() | Inicializa una nueva instancia de la clase [XmlSchemaSimpleTypeRestriction](./). |
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
