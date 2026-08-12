---
title: "Clase System::Xml::Schema::XmlSchemaIdentityConstraint"
linktitle: "XmlSchemaIdentityConstraint"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaIdentityConstraint. Clase para las restricciones de identidad: elementos key, keyref y unique en C++."
type: docs
weight: 3400
url: /es/cpp/system.xml.schema/xmlschemaidentityconstraint/
---
## XmlSchemaIdentityConstraint class


Clase para las restricciones de identidad: los elementos **key**, **keyref** y **unique**.

```cpp
class XmlSchemaIdentityConstraint : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Fields](./get_fields/)() | Devuelve la colección de campos que se aplican como hijos para el selector de expresión del Lenguaje de Ruta XML ([XPath](../../system.xml.xpath/)). |
| [get_Name](./get_name/)() | Devuelve el nombre de la restricción de identidad. |
| [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado de la restricción de identidad, que contiene la interpretación posterior a la compilación del valor **QualifiedName**. |
| [get_Selector](./get_selector/)() | Devuelve el elemento **selector** de la expresión [XPath](../../system.xml.xpath/). |
| [set_Name](./set_name/)(const String\&) | Establece el nombre de la restricción de identidad. |
| [set_Selector](./set_selector/)(const SharedPtr\<XmlSchemaXPath\>\&) | Establece el elemento **selector** de la expresión [XPath](../../system.xml.xpath/). |
| [XmlSchemaIdentityConstraint](./xmlschemaidentityconstraint/)() | Inicializa una nueva instancia de la clase [XmlSchemaIdentityConstraint](./). |
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
