---
title: "Clase System::Xml::Schema::XmlSchemaSequence"
linktitle: "XmlSchemaSequence"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::Schema::XmlSchemaSequence. Representa el elemento **secuencia** (compositor) del XML Schema según lo especificado por el World Wide Web Consortium (W3C). La **secuencia** requiere que los elementos del grupo aparezcan en el orden especificado dentro del elemento contenedor en C++."
type: docs
weight: 5700
url: /es/cpp/system.xml.schema/xmlschemasequence/
---
## XmlSchemaSequence class


Representa el elemento **secuencia** (compositor) del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). La **secuencia** requiere que los elementos del grupo aparezcan en la secuencia especificada dentro del elemento contenedor.

```cpp
class XmlSchemaSequence : public System::Xml::Schema::XmlSchemaGroupBase
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Items](./get_items/)() override | Los elementos contenidos dentro del compositor. Colección de [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaSequence](./) o [XmlSchemaAny](../xmlschemaany/). |
| [XmlSchemaSequence](./xmlschemasequence/)() | Inicializa una nueva instancia de la clase [XmlSchemaSequence](./). |
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
