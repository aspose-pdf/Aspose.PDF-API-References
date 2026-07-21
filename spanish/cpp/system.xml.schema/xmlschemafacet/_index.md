---
title: "System::Xml::Schema::XmlSchemaFacet class"
linktitle: "XmlSchemaFacet"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaFacet class. Una clase base para todas las facetas que se utilizan cuando los tipos simples se derivan por restricción en C++."
type: docs
weight: 2900
url: /es/cpp/system.xml.schema/xmlschemafacet/
---
## XmlSchemaFacet class


Una clase base para todas las facetas que se utilizan cuando los tipos simples se derivan por restricción.

```cpp
class XmlSchemaFacet : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [get_IsFixed](./get_isfixed/)() | Devuelve información que indica que esta faceta está fija. |
| [get_Value](./get_value/)() | Devuelve el atributo **value** de la faceta. |
| virtual [set_IsFixed](./set_isfixed/)(bool) | Establece información que indica que esta faceta está fija. |
| [set_Value](./set_value/)(const String\&) | Establece el atributo **value** de la faceta. |
| [XmlSchemaFacet](./xmlschemafacet/)() | Inicializa una nueva instancia de la clase [XmlSchemaFacet](./). |
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
