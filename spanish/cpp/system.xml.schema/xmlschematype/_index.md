---
title: "Clase System::Xml::Schema::XmlSchemaType"
linktitle: "XmlSchemaType"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaType. La clase base para todos los tipos simples y tipos complejos en C++."
type: docs
weight: 6800
url: /es/cpp/system.xml.schema/xmlschematype/
---
## XmlSchemaType class


La clase base para todos los tipos simples y tipos complejos.

```cpp
class XmlSchemaType : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BaseSchemaType](./get_baseschematype/)() | Devuelve el tipo de objeto posterior a la compilación o el tipo de datos incorporado del Lenguaje de Definición XML [Schema](../) (XSD), elemento simpleType o elemento complexType. Este es un valor del conjunto de información posterior a la compilación del esquema. |
| [get_BaseXmlSchemaType](./get_basexmlschematype/)() | Devuelve el valor posterior a la compilación para el tipo base de este tipo de esquema. |
| [get_Datatype](./get_datatype/)() | Devuelve el valor posterior a la compilación para el tipo de datos del tipo complejo. |
| [get_DerivedBy](./get_derivedby/)() | Devuelve la información posterior a la compilación sobre cómo este elemento se derivó de su tipo base. |
| [get_Final](./get_final/)() | Devuelve el atributo final de la derivación del tipo que indica si se permiten más derivaciones. |
| [get_FinalResolved](./get_finalresolved/)() | Devuelve la interpretación posterior a la compilación del valor [XmlSchemaType::get_Final](./get_final/). |
| virtual [get_IsMixed](./get_ismixed/)() | Devuelve un valor que indica si este tipo tiene un modelo de contenido mixto. Esta llamada solo es válida en un tipo complejo. |
| [get_Name](./get_name/)() | Devuelve el nombre del tipo. |
| [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado para el tipo construido a partir del atributo **Name** de este tipo. Este es un valor posterior a la compilación del esquema. |
| [get_TypeCode](./get_typecode/)() | Devuelve el [XmlTypeCode](../xmltypecode/) del tipo. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(XmlTypeCode) | Devuelve un [XmlSchemaComplexType](../xmlschemacomplextype/) que representa el tipo complejo incorporado del tipo complejo especificado. |
| static [GetBuiltInComplexType](./getbuiltincomplextype/)(const SharedPtr\<XmlQualifiedName\>\&) | Devuelve un [XmlSchemaComplexType](../xmlschemacomplextype/) que representa el tipo complejo incorporado del tipo complejo especificado por nombre calificado. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(const SharedPtr\<XmlQualifiedName\>\&) | Devuelve un [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple que se especifica por el nombre calificado. |
| static [GetBuiltInSimpleType](./getbuiltinsimpletype/)(XmlTypeCode) | Devuelve un [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple especificado. |
| static [IsDerivedFrom](./isderivedfrom/)(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) | Devuelve un valor que indica si el tipo de esquema derivado especificado se deriva del tipo de esquema base especificado. |
| [set_Final](./set_final/)(XmlSchemaDerivationMethod) | Establece el atributo final de la derivación del tipo que indica si se permiten más derivaciones. |
| virtual [set_IsMixed](./set_ismixed/)(bool) | Establece un valor que indica si este tipo tiene un modelo de contenido mixto. Esta llamada solo es válida en un tipo complejo. |
| [set_Name](./set_name/)(const String\&) | Establece el nombre del tipo. |
| [XmlSchemaType](./xmlschematype/)() | Inicializa una nueva instancia de la clase [XmlSchemaType](./). |
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
