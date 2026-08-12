---
title: "Clase System::Xml::Schema::XmlSchemaChoice"
linktitle: "XmlSchemaChoice"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaChoice. Representa el elemento choice (compositor) del XML Schema según lo especificado por el World Wide Web Consortium (W3C). El choice permite que solo uno de sus hijos aparezca en una instancia en C++."
type: docs
weight: 1400
url: /es/cpp/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice class


Representa el elemento **choice** (compositor) del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). El **choice** permite que solo uno de sus hijos aparezca en una instancia.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Items](./get_items/)() override | Devuelve la colección de los elementos contenidos con el compositor (**choice**): [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/), o [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaChoice](./xmlschemachoice/)() | Inicializa una nueva instancia de la clase [XmlSchemaChoice](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Observaciones



Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree instancias de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

## Ver también

* Class [XmlSchemaGroupBase](../xmlschemagroupbase/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
