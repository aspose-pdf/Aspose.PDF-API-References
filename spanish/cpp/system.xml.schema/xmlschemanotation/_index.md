---
title: "System::Xml::Schema::XmlSchemaNotation class"
linktitle: "XmlSchemaNotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Schema::XmlSchemaNotation class. Representa el elemento notación del XML Schema según lo especificado por el World Wide Web Consortium (W3C). Una declaración de notación de XML Schema es una reconstrucción de las declaraciones NOTATION de XML 1.0. El propósito de las notaciones es describir el formato de datos no XML dentro de un documento XML en C++."
type: docs
weight: 4800
url: /es/cpp/system.xml.schema/xmlschemanotation/
---
## XmlSchemaNotation class


Representa el elemento **notation** del XML [Schema](../) según lo especificado por el World Wide [Web](../../system.web/) Consortium (W3C). Una declaración **notation** de XML [Schema](../) es una reconstrucción de las declaraciones NOTATION de **XML** 1.0. El propósito de las notaciones es describir el formato de datos no XML dentro de un documento XML.

```cpp
class XmlSchemaNotation : public System::Xml::Schema::XmlSchemaAnnotated
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Name](./get_name/)() | Devuelve el nombre de la notación. |
| [get_Public](./get_public/)() | Devuelve el identificador **public**. |
| [get_System](./get_system/)() | Devuelve el identificador **system**. |
| [set_Name](./set_name/)(const String\&) | Establece el nombre de la notación. |
| [set_Public](./set_public/)(const String\&) | Establece el identificador **public**. |
| [set_System](./set_system/)(const String\&) | Establece el identificador **system**. |
| [XmlSchemaNotation](./xmlschemanotation/)() | Inicializa una nueva instancia de la clase [XmlSchemaNotation](./). |
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
