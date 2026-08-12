---
title: "Clase System::Xml::Schema::XmlSchemaAttribute"
linktitle: "XmlSchemaAttribute"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaAttribute. Representa el elemento atributo del XML Schema según lo especificado por el Consorcio World Wide Web (W3C). Los atributos proporcionan información adicional para otros elementos del documento. La etiqueta de atributo se anida entre las etiquetas del elemento de un documento para el esquema. El documento XML muestra los atributos como elementos nombrados en la etiqueta de apertura de un elemento en C++."
type: docs
weight: 1100
url: /es/cpp/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute class


Representa el elemento **attribute** del XML [Schema](../) según lo especificado por el Consorcio World Wide [Web](../../system.web/) (W3C). Los atributos proporcionan información adicional para otros elementos del documento. La etiqueta de atributo se anida entre las etiquetas del elemento de un documento para el esquema. El documento XML muestra los atributos como elementos nombrados en la etiqueta de apertura de un elemento.

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AttributeSchemaType](./get_attributeschematype/)() | Devuelve un objeto [XmlSchemaSimpleType](../xmlschemasimpletype/) que representa el tipo del atributo basado en el valor [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) del atributo. |
| [get_AttributeType](./get_attributetype/)() | Devuelve el objeto basado en el valor [XmlSchemaAttribute::get_SchemaType](./get_schematype/) o [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) del atributo que contiene la interpretación posterior a la compilación del valor **AttributeType**. |
| [get_DefaultValue](./get_defaultvalue/)() | Devuelve el valor predeterminado del atributo. |
| [get_FixedValue](./get_fixedvalue/)() | Devuelve el valor fijo del atributo. |
| [get_Form](./get_form/)() | Devuelve la forma del atributo. |
| [get_Name](./get_name/)() | Devuelve el nombre del atributo. |
| [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado del atributo. |
| [get_RefName](./get_refname/)() | Devuelve el nombre de un atributo declarado en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [get_SchemaType](./get_schematype/)() | Devuelve el tipo de atributo a un tipo simple. |
| [get_SchemaTypeName](./get_schematypename/)() | Devuelve el nombre del tipo simple definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [get_Use](./get_use/)() | Devuelve información sobre cómo se usa el atributo. |
| [set_DefaultValue](./set_defaultvalue/)(const String\&) | Establece el valor predeterminado del atributo. |
| [set_FixedValue](./set_fixedvalue/)(const String\&) | Establece el valor fijo del atributo. |
| [set_Form](./set_form/)(XmlSchemaForm) | Establece la forma del atributo. |
| [set_Name](./set_name/)(const String\&) | Establece el nombre del atributo. |
| [set_RefName](./set_refname/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre de un atributo declarado en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [set_SchemaType](./set_schematype/)(const SharedPtr\<XmlSchemaSimpleType\>\&) | Establece el tipo de atributo a un tipo simple. |
| [set_SchemaTypeName](./set_schematypename/)(const SharedPtr\<XmlQualifiedName\>\&) | Establece el nombre del tipo simple definido en este esquema (o en otro esquema indicado por el espacio de nombres especificado). |
| [set_Use](./set_use/)(XmlSchemaUse) | Establece información sobre cómo se usa el atributo. |
| [XmlSchemaAttribute](./xmlschemaattribute/)() | Inicializa una nueva instancia de la clase [XmlSchemaAttribute](./). |
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
