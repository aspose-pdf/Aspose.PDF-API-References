---
title: "System::Xml::Schema::XmlSchemaGroup clase"
linktitle: "XmlSchemaGroup"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaGroup clase. Representa el elemento **group** del XML Schema según lo especificado por el Consorcio de la World Wide Web (W3C). Esta clase define grupos a nivel **schema** que son referenciados desde los tipos complejos. Agrupa un conjunto de declaraciones de elementos para que puedan incorporarse como un **group** en definiciones de tipos complejos en C++."
type: docs
weight: 3100
url: /es/cpp/system.xml.schema/xmlschemagroup/
---
## XmlSchemaGroup class


Representa el elemento **group** del XML [Schema](../) según lo especificado por el Consorcio de la [Web](../../system.web/) (W3C). Esta clase define grupos a nivel **schema** que son referenciados desde los tipos complejos. Agrupa un conjunto de declaraciones de elementos para que puedan incorporarse como un **group** en definiciones de tipos complejos.

```cpp
class XmlSchemaGroup : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Name](./get_name/)() | Devuelve el nombre del grupo del esquema. |
| [get_Particle](./get_particle/)() | Devuelve uno de los [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), o [XmlSchemaSequence](../xmlschemasequence/) clases. |
| [get_QualifiedName](./get_qualifiedname/)() | Devuelve el nombre calificado del grupo del esquema. |
| [set_Name](./set_name/)(const String\&) | Establece el nombre del grupo del esquema. |
| [set_Particle](./set_particle/)(const SharedPtr\<XmlSchemaGroupBase\>\&) | Establece uno de los [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/), o [XmlSchemaSequence](../xmlschemasequence/) clases. |
| [XmlSchemaGroup](./xmlschemagroup/)() | Inicializa una nueva instancia de la clase [XmlSchemaGroup](./). |
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
